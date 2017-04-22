youtube-dl-api-server
=====================

A REST API server for getting the info for videos from different sites, powered by `youtube-dl <http://rg3.github.io/youtube-dl/>`_.
The installation instructions and the documentation are available at `Read the Docs <https://youtube-dl-api-server.readthedocs.org/>`_.

About
-----

``youtube-dl-api-server`` is released to the public domain, read the `license <LICENSE>`_ for more info.


Query Parameters
-----
url:               The video url
format:		         Video format code. See options.py for more information.
playliststart:     Playlist item to start at.
playlistend:       Playlist item to end at.
playlist_items:    Specific indices of playlist to download.
matchtitle:        Download only matching titles.
rejecttitle:       Reject downloads for matching titles.
playlistreverse:   Download playlist items in reverse order.
subtitlesformat:   The format code for subtitles
subtitleslangs:    List of languages of the subtitles to download
allsubtitles:      Downloads all the subtitles of the video
                   (requires writesubtitles or writeautomaticsub)
writesubtitles:    Write the video subtitles to a file
writeautomaticsub: Write the automatically generated subtitles to a file
