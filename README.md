1  +# Auto detect text files and perform LF normalization
2	+* text=auto
3	+
4	+# Custom for Visual Studio
5	+*.cs     diff=csharp
6	+*.sln    merge=union
7	+*.csproj merge=union
8	+*.vbproj merge=union
9	+*.fsproj merge=union
10	+*.dbproj merge=union
11	+
12	+# Standard to msysgit
13	+*.doc	 diff=astextplain
14	+*.DOC	 diff=astextplain
15	+*.docx diff=astextplain
16	+*.DOCX diff=astextplain
17	+*.dot  diff=astextplain
18	+*.DOT  diff=astextplain
19	+*.pdf  diff=astextplain
20	+*.PDF	 diff=astextplain
21	+*.rtf	 diff=astextplain
22	+*.RTF	 diff=astextplain
Mylifebook
==========
+#################
+## Eclipse
+#################
+
+*.pydevproject
+.project
+.metadata
+bin/
+tmp/
+*.tmp
+*.bak
+*.swp
+*~.nib
+local.properties
+.classpath
+.settings/
+.loadpath
+
+# External tool builders
+.externalToolBuilders/
+
+# Locally stored "Eclipse launch configurations"
+*.launch
+
+# CDT-specific
+.cproject
+
+# PDT-specific
+.buildpath
+
+
+#################
+## Visual Studio
+#################
+
+## Ignore Visual Studio temporary files, build results, and
+## files generated by popular Visual Studio add-ons.
+
+# User-specific files
+*.suo
+*.user
+*.sln.docstates
+
+# Build results
+[Dd]ebug/
+[Rr]elease/
+*_i.c
+*_p.c
+*.ilk
+*.meta
+*.obj
+*.pch
+*.pdb
+*.pgc
+*.pgd
+*.rsp
+*.sbr
+*.tlb
+*.tli
+*.tlh
+*.tmp
+*.vspscc
+.builds
+*.dotCover
+
+## TODO: If you have NuGet Package Restore enabled, uncomment this
+#packages/
+
+# Visual C++ cache files
+ipch/
+*.aps
+*.ncb
+*.opensdf
+*.sdf
+
+# Visual Studio profiler
+*.psess
+*.vsp
+
+# ReSharper is a .NET coding add-in
+_ReSharper*
+
+# Installshield output folder
+[Ee]xpress
+
+# DocProject is a documentation generator add-in
+DocProject/buildhelp/
+DocProject/Help/*.HxT
+DocProject/Help/*.HxC
+DocProject/Help/*.hhc
+DocProject/Help/*.hhk
+DocProject/Help/*.hhp
+DocProject/Help/Html2
+DocProject/Help/html
+
+# Click-Once directory
+publish
+
+# Others
+[Bb]in
+[Oo]bj
+sql
+TestResults
+*.Cache
+ClientBin
+stylecop.*
+~$*
+*.dbmdl
+Generated_Code #added for RIA/Silverlight projects
+
+# Backup & report files from converting an old project file to a newer
+# Visual Studio version. Backup files are not needed, because we have git ;-)
+_UpgradeReport_Files/
+Backup*/
+UpgradeLog*.XML
+
+
+
+############
+## Windows
+############
+
+# Windows image file caches
+Thumbs.db
+
+# Folder config file
+Desktop.ini
+
+
+#############
+## Python
+#############
+
+*.py[co]
+
+# Packages
+*.egg
+*.egg-info
+dist
+build
+eggs
+parts
+bin
+var
+sdist
+develop-eggs
+.installed.cfg
+
+# Installer logs
+pip-log.txt
+
+# Unit test / coverage reports
+.coverage
+.tox
+
+#Translations
+*.mo
+
+#Mr Developer
+.mr.developer.cfg
+
+# Mac crap

