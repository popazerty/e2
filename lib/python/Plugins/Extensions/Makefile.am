installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer SocketMMI DVDBurn \
	IniMyTube IniSHOUTcast IniLastFM IniZapHistoryBrowser AccuWeather IniGmailReader \
	IniEcasa IniWebcamViewer RemoteIPTVClient

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

install_PYTHON = __init__.py
