# A general .gitignore file for .NET projects.
# Based on various sources, including Visual Studio, .NET, Rider, and macOS/Windows system files.

##################
# Environment & User-Specific Files #
##################
.env
*.rsuser
*.suo
*.user
*.userosscache
*.sln.docstates
*.userprefs
mono_crash.*

##################
# Build Results #
##################
[Dd]ebug/
[Dd]ebugPublic/
[Rr]elease/
[Rr]eleases/
x64/
x86/
[Ww][Ii][Nn]32/
[Aa][Rr][Mm]/
[Aa][Rr][Mm]64/
bld/
[Bb]in/
[Oo]bj/
[Ll]og/
[Ll]ogs/
BenchmarkDotNet.Artifacts/

#####################
# Visual Studio Files #
#####################
.vs/
.vscode/
Generated\ Files/

# Visual Studio Profiler
*.psess
*.vsp
*.vspx
*.sap

# Visual Studio Cache Files
*.[Cc]ache
!?*.[Cc]ache/

#################
# Test Results #
#################
[Tt]est[Rr]esult*/
[Bb]uild[Ll]og.*
*.coverage
*.coveragexml
TestResult.xml
nunit-*.xml

#################
# .NET Specific #
#################
project.lock.json
project.fragment.lock.json
project.assets.json
artifacts/
.tye/
ScaffoldingReadMe.txt
StyleCopReport.xml

#################
# Build Files #
#################
*_i.c
*_p.c
*_h.h
*.ilk
*.meta
*.obj
*.iobj
*.pch
*.pdb
*.ipdb
*.pgc
*.pgd
*.rsp
!Directory.Build.rsp
*.sbr
*.tlb
*.tli
*.tlh
*.tmp
*.tmp_proj
*_wpftmp.csproj
*.log
*.tlog
*.vspscc
*.vssscc
.builds
*.pidb
*.svclog
*.scc

###########################
# Visual C++ Cache Files #
###########################
ipch/
*.aps
*.ncb
*.opendb
*.opensdf
*.sdf
*.cachefile
*.VC.db
*.VC.VC.opendb

######################
# TeamCity and ReSharper #
######################
_TeamCity*
_ReSharper*/
*.[Rr]e[Ss]harper
*.DotSettings.user

##################
# Coverage Tools #
##################
.axoCover/*
coverage*.json
coverage*.xml
coverage*.info
*.dotCover

#################
# Chutzpah Test #
#################
_Chutzpah*

######################
# NCrunch and MightyMoose #
######################
_NCrunch_*
.*crunch*.local.xml
nCrunchTemp_*
*.mm.*
AutoTest.Net/

###################
# Web Workbench (SASS) #
###################
.sass-cache/

######################
# InstallShield Output #
######################
[Ee]xpress/

######################
# DocProject Generator #
######################
DocProject/buildhelp/
DocProject/Help/*.HxT
DocProject/Help/*.HxC
DocProject/Help/*.hhc
DocProject/Help/*.hhk
DocProject/Help/*.hhp
DocProject/Help/Html2
DocProject/Help/html

######################
# Publish Web Output #
######################
publish/
PublishScripts/
*.[Pp]ublish.xml
*.azurePubxml
*.pubxml
*.publishproj

######################
# NuGet Packages #
######################
.nuget/
*.nupkg
*.snupkg
**/[Pp]ackages/*
!**/[Pp]ackages/build/
*.nuget.props
*.nuget.targets

######################
# Microsoft Azure #
######################
csx/
*.build.csdef
ecf/
rcf/

######################
# Windows Store Apps #
######################
AppPackages/
BundleArtifacts/
Package.StoreAssociation.xml
_pkginfo.txt
*.appx
*.appxbundle
*.appxupload

#################
# SQL Server #
#################
*.mdf
*.ldf
*.ndf

######################
# Business Intelligence #
######################
*.rdl.data
*.bim.layout
*.bim_*.settings
*.rptproj.rsuser
*- [Bb]ackup.rdl
*- [Bb]ackup ([0-9]).rdl
*- [Bb]ackup ([0-9][0-9]).rdl

######################
# Microsoft Fakes #
######################
FakesAssemblies/

#################
# GhostDoc #
#################
*.GhostDoc.xml

###################
# Node.js #
###################
.ntvs_analysis.dat
node_modules/
bower_components/

#####################
# Visual Studio 6 #
#####################
*.plg
*.opt
*.vbw
*.vbp
*.dsw
*.dsp
*.ncb
*.aps

######################
# LightSwitch Output #
######################
**/*.HTMLClient/GeneratedArtifacts
**/*.DesktopClient/GeneratedArtifacts
**/*.DesktopClient/ModelManifest.xml
**/*.Server/GeneratedArtifacts
**/*.Server/ModelManifest.xml
_Pvt_Extensions

######################
# Paket Dependency Manager #
######################
.paket/paket.exe
paket-files/

######################
# FAKE - F# Make #
######################
.fake/

######################
# CodeRush #
######################
.cr/personal

######################
# Python #
######################
__pycache__/
*.pyc

######################
# Cake #
######################
# tools/**
# !tools/packages.config

######################
# Tabs Studio #
######################
*.tss

######################
# Telerik JustMock #
######################
*.jmconfig

######################
# BizTalk #
######################
*.btp.cs
*.btm.cs
*.odx.cs
*.xsd.cs

######################
# OpenCover #
######################
OpenCover/

######################
# Azure Stream Analytics #
######################
ASALocalRun/

######################
# MSBuild Logs #
######################
*.binlog

######################
# NVidia Nsight GPU Debugger #
######################
*.nvuser

######################
# Rider IDE #
######################
*.sln.iml
.idea/

######################
# Local History #
######################
.localhistory/
.vshistory/
.history/

######################
# Windows Installer #
######################
*.cab
*.msi
*.msix
*.msm
*.msp

######################
# JetBrains Rider #
######################
.idea/

######################
# Visual Studio for Mac #
######################
Makefile.in
*.userprefs
*.usertasks
config.make
config.status
aclocal.m4
install-sh
autom4te.cache/
*.tar.gz
tarballs/
test-results/

######################
# Mac Bundle #
######################
*.dmg
*.app

######################
# macOS System Files #
######################
.DS_Store
.AppleDouble
.LSOverride
Icon
._*
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

######################
# Windows System Files #
######################
Thumbs.db
ehthumbs.db
ehthumbs_vista.db
*.stackdump
[Dd]esktop.ini
$RECYCLE.BIN/
*.lnk

######################
# Vim Swap Files #
######################
*.swp
