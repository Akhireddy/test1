if BUILD_AUTOVERSIONING
MAYBE_AUTOVERSIONING=AutoVersioning
endif

if BUILD_BROWSETRACKER
MAYBE_BROWSETRACKER=BrowseTracker
endif

if BUILD_BYOGAMES
MAYBE_BYOGAMES=byogames
endif

if BUILD_CBKODERS
MAYBE_CBKODERS=cb_koders
endif

if BUILD_CODESNIPPETS
MAYBE_CODESNIPPETS=codesnippets
endif

if BUILD_CODESTAT
MAYBE_CODESTAT=codestat
endif

if BUILD_COPYSTRINGS
MAYBE_COPYSTRINGS=copystrings
endif

if BUILD_CSCOPE
MAYBE_CSCOPE=Cscope
endif

if BUILD_DOXYBLOCKS
MAYBE_DOXYBLOCKS=DoxyBlocks
endif

if BUILD_DRAGSCROLL
MAYBE_DRAGSCROLL=dragscroll
endif

if BUILD_EDITORCONFIG
MAYBE_EDITORCONFIG=EditorConfig
endif

if BUILD_EDITORTWEAKS
MAYBE_EDITORTWEAKS=EditorTweaks
endif

if BUILD_ENVVARS
MAYBE_ENVVARS=envvars
endif

if BUILD_FILEMANAGER
MAYBE_FILEMANAGER=FileManager
endif

if BUILD_HELP
MAYBE_HELP=help_plugin
endif

if BUILD_HEADERFIXUP
MAYBE_HEADERFIXUP=headerfixup
endif

if BUILD_KEYBINDER
MAYBE_KEYBINDER=keybinder
endif

if BUILD_LIBFINDER
MAYBE_LIBFINDER=wxContribItems lib_finder
endif

if BUILD_PROFILER
MAYBE_PROFILER=profiler
endif

if BUILD_PROJECTOPTIONSMANIPULATOR
MAYBE_PROJECTOPTIONSMANIPULATOR=ProjectOptionsManipulator
endif

if BUILD_REGEX
MAYBE_REGEX=regex_testbed
endif

if BUILD_REOPENEDITOR
MAYBE_REOPENEDITOR=ReopenEditor
endif

if BUILD_EXPORTER
MAYBE_EXPORTER=source_exporter
endif

if BUILD_SMARTINDENT
MAYBE_SMARTINDENT=SmartIndent
endif

if BUILD_SPELLCHECKER
MAYBE_SPELLCHECKER=SpellChecker
endif

if BUILD_SYMTAB
MAYBE_SYMTAB=symtab
endif

if BUILD_THREADSEARCH
MAYBE_THREADSEARCH=wxContribItems ThreadSearch
endif

if BUILD_TOOLSPLUS
MAYBE_TOOLSPLUS=ToolsPlus
endif

if BUILD_VALGRIND
MAYBE_VALGRIND=Valgrind
endif

if BUILD_WXCONTRIB
MAYBE_WXCONTRIB=wxContribItems
endif

if BUILD_WXSMITH
MAYBE_WXSMITH=wxSmith
endif

if BUILD_WXSMITHCONTRIB
MAYBE_WXSMITHCONTRIB=wxSmith wxContribItems wxSmithContribItems
endif

if BUILD_WXSMITHAUI
MAYBE_WXSMITHAUI=wxSmith wxSmithAui
endif

if BUILD_HEXEDITOR
MAYBE_HEXEDITOR=HexEditor
endif

if BUILD_INCSEARCH
MAYBE_INCSEARCH=IncrementalSearch
endif

if BUILD_MOUSESAP
MAYBE_MOUSESAP=MouseSap
endif

if BUILD_NASSISHNEIDERMAN
MAYBE_NASSISHNEIDERMAN=NassiShneiderman
endif

if BUILD_CCCC
MAYBE_CCCC=Cccc
endif

if BUILD_CPPCHECK
MAYBE_CPPCHECK=CppCheck
endif

SUBDIRS = $(MAYBE_AUTOVERSIONING) \
		$(MAYBE_BROWSETRACKER) \
		$(MAYBE_BYOGAMES) \
		$(MAYBE_CBKODERS) \
		$(MAYBE_CCCC) \
		$(MAYBE_CODESNIPPETS) \
		$(MAYBE_CODESTAT) \
		$(MAYBE_COPYSTRINGS) \
		$(MAYBE_CPPCHECK) \
		$(MAYBE_CSCOPE) \
		$(MAYBE_DOXYBLOCKS) \
		$(MAYBE_DRAGSCROLL) \
		$(MAYBE_EDITORCONFIG) \
		$(MAYBE_EDITORTWEAKS) \
		$(MAYBE_ENVVARS) \
		$(MAYBE_FILEMANAGER) \
		$(MAYBE_HEADERFIXUP) \
		$(MAYBE_HELP) \
		$(MAYBE_HEXEDITOR) \
		$(MAYBE_INCSEARCH) \
		$(MAYBE_KEYBINDER) \
		$(MAYBE_LIBFINDER) \
		$(MAYBE_MOUSESAP) \
		$(MAYBE_NASSISHNEIDERMAN) \
		$(MAYBE_PROFILER) \
		$(MAYBE_PROJECTOPTIONSMANIPULATOR) \
		$(MAYBE_EXPORTER) \
		$(MAYBE_SYMTAB) \
		$(MAYBE_SMARTINDENT) \
		$(MAYBE_SPELLCHECKER) \
		$(MAYBE_REGEX) \
		$(MAYBE_REOPENEDITOR) \
		$(MAYBE_THREADSEARCH) \
		$(MAYBE_TOOLSPLUS) \
		$(MAYBE_VALGRIND) \
		$(MAYBE_WXCONTRIB) \
		$(MAYBE_WXSMITH) \
		$(MAYBE_WXSMITHCONTRIB) \
		$(MAYBE_WXSMITHAUI)

DIST_SUBDIRS = AutoVersioning \
		BrowseTracker \
		byogames \
		cb_koders \
		Cccc \
		codesnippets \
		codestat \
		copystrings \
		CppCheck \
		Cscope \
		devpak_plugin \
		DoxyBlocks \
		dragscroll \
		EditorConfig \
		EditorTweaks \
		envvars \
		FileManager \
		headerfixup \
		help_plugin \
		HexEditor \
		keybinder \
		IncrementalSearch \
		lib_finder \
		MouseSap \
		NassiShneiderman \
		profiler \
		ProjectOptionsManipulator \
		source_exporter \
		SmartIndent \
		SpellChecker \
		symtab \
		regex_testbed \
		ReopenEditor \
		ThreadSearch \
		ToolsPlus \
		Valgrind \
		wxContribItems \
		wxSmith \
		wxSmithContribItems \
		wxSmithAui \
		wxSmithDateTimePicker \
		wxSmithDemo \
		wxSmithIExplore \
		wxSmithSTC

EXTRA_DIST = rndgen
if ENABLE_FORTRAN
EXTRA_DIST += $(srcdir)/FortranProject/*.h \
		$(srcdir)/FortranProject/*.cpp \
		$(srcdir)/FortranProject/*.xml \
		$(srcdir)/FortranProject/*.cbp \
		$(srcdir)/FortranProject/update* \
		$(srcdir)/FortranProject/images/*.png \
		$(srcdir)/FortranProject/images/16x16/*.png \
		$(srcdir)/FortranProject/images/fortranproject/*.png \
		$(srcdir)/FortranProject/images/fortranproject/*.f90 \
		$(srcdir)/FortranProject/resources/*.xrc
endif

