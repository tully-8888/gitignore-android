# gitignore-android

# Default ignored files
/shelf/
/workspace.xml

*.iml
.gradle
/local.properties
/.idea
/.idea/caches
/.idea/libraries
/.idea/modules.xml
/.idea/workspace.xml
/.idea/navEditor.xml
/.idea/assetWizardSettings.xml
.DS_Store
/build
/build-cache
/captures
.externalNativeBuild
.cxx
local.properties

### Windows template
# Windows thumbnail cache files
Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file
*.stackdump

# Folder config file
[Dd]esktop.ini

# Recycle Bin used on file shares
$RECYCLE.BIN/

# Windows Installer files
*.cab
*.msi
*.msix
*.msm
*.msp

# Windows shortcuts
*.lnk

### macOS template
# General
.AppleDouble
.LSOverride

# Icon must end with two \r
Icon

# Thumbnails
._*

# Files that might appear in the root of a volume
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

### Linux template
*~

# temporary files which can be created if a process still has a handle open of a deleted file
.fuse_hidden*

# KDE directory preferences
.directory

# Linux trash folder which might appear on any partition or disk
.Trash-*

# .nfs files are created when an open file is removed but is still being accessed
.nfs*

### JetBrains template
# Covers JetBrains IDEs: IntelliJ, RubyMine, PhpStorm, AppCode, PyCharm, CLion, Android Studio and WebStorm
# Reference: https://intellij-support.jetbrains.com/hc/en-us/articles/206544839

*.iml
*.ipr
*.iws
/.idea/*

# Exclude non-user-specific stuff
!.idea/.name
!.idea/codeInsightSettings.xml
!.idea/codeStyles/
!.idea/copyright/
!.idea/dataSources.xml
!.idea/detekt.xml
!.idea/encodings.xml
!.idea/externalDependencies.xml
!.idea/file.template.settings.xml
!.idea/fileTemplates/
!.idea/icon.svg
!.idea/inspectionProfiles/
!.idea/runConfigurations/
!.idea/scopes/
!.idea/vcs.xml

### Kotlin template
# Compiled class file
*.class

# Log file
*.log

# Package Files #
*.jar
*.war
*.nar
*.ear
*.zip
*.tar.gz
*.rar

# virtual machine crash logs, see http://www.java.com/en/download/help/error_hotspot.xml
hs_err_pid*

# Note that you may need to exclude by hand other folders
# named build if necessary (e.g., in src/)
**/build/

# Avoid ignoring Gradle wrapper jar file (.jar files are usually ignored)
!gradle/wrapper/gradle-wrapper.jar

# Cache of project
.gradletasknamecache

### Android-specific stuff
# Built application files
*.apk
*.ap_
*.aab
*.apks

# Files for the Dalvik VM
*.dex

# Generated files
bin/
gen/
