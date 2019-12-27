Attempt to build a [kiwix-desktop](https://github.com/kiwix/kiwix-desktop) snap. 

Currently builds but does not run.

```
$ kiwix-desktop                                                                                                                                             
Qt: Session management error: None of the authentication protocols specified are supported
Library directory : "/home/alan/snap/kiwix-desktop/x3/.local/share/kiwix"
Cannot launch                       
: No such file or directory 
 curl_easy_perform() failed.
                                                   
libcurl: (7) Failed to connect to localhost port 42042: Connection refused
Cannot create downloader Cannot connect to aria2c rpc
Cannot launch
: No such file or directory
 curl_easy_perform() failed.

libcurl: (7) Failed to connect to localhost port 42042: Connection refused
Cannot create downloader Cannot connect to aria2c rpc
Cannot launch
: No such file or directory
 curl_easy_perform() failed.

libcurl: (7) Failed to connect to localhost port 42042: Connection refused
Cannot create downloader Cannot connect to aria2c rpc
Cannot launch
: No such file or directory
 curl_easy_perform() failed.

libcurl: (7) Failed to connect to localhost port 42042: Connection refused
Cannot create downloader Cannot connect to aria2c rpc
Cannot launch
: No such file or directory
 curl_easy_perform() failed.

libcurl: (7) Failed to connect to localhost port 42042: Connection refused
Cannot create downloader Cannot connect to aria2c rpc

propsReply "An AppArmor policy prevents this sender from sending this message to this recipient; type=\"method_call\", sender=\":1.4002\" (uid=1000 pid=21585 comm=\"/snap/kiwix-desktop/x3/usr/local/bin/kiw
ix-desktop\" label=\"snap.kiwix-desktop.kiwix-desktop (enforce)\") interface=\"org.freedesktop.DBus.Properties\" member=\"GetAll\" error name=\"(unset)\" requested_reply=\"0\" destination=\"org.freedesktop
.NetworkManager\" (uid=0 pid=5819 comm=\"/usr/sbin/NetworkManager --no-daemon \" label=\"unconfined\")"
nmReply "An AppArmor policy prevents this sender from sending this message to this recipient; type=\"method_call\", sender=\":1.4002\" (uid=1000 pid=21585 comm=\"/snap/kiwix-desktop/x3/usr/local/bin/kiwix-
desktop\" label=\"snap.kiwix-desktop.kiwix-desktop (enforce)\") interface=\"org.freedesktop.NetworkManager\" member=\"GetDevices\" error name=\"(unset)\" requested_reply=\"0\" destination=\"org.freedesktop
.NetworkManager\" (uid=0 pid=5819 comm=\"/usr/sbin/NetworkManager --no-daemon \" label=\"unconfined\")"
"Object path cannot be empty"
Installed Qt WebEngine locales directory not found at location /usr/share/qt5/translations/qtwebengine_locales. Trying application directory...
Qt WebEngine locales directory not found at location /snap/kiwix-desktop/x3/usr/local/bin/qtwebengine_locales. Trying fallback directory... Translations MAY NOT not be correct.
Path override failed for key ui::DIR_LOCALES and path '/home/alan/snap/kiwix-desktop/x3/.kiwix-desktop'
Qt WebEngine resources not found at /usr/share/qt5/resources. Trying parent directory...
Qt WebEngine resources not found at /usr/share/qt5. Trying application directory...
Qt WebEngine resources not found at /snap/kiwix-desktop/x3/usr/local/bin. Trying fallback directory... The application MAY NOT work.
[1227/115932.327406:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.kiwix-desktop/qtwebengine_resources.pak
Some features may not be available.
[1227/115932.327438:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.kiwix-desktop/qtwebengine_resources_100p.pak
Some features may not be available.
[1227/115932.327451:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.kiwix-desktop/qtwebengine_resources_200p.pak
Some features may not be available.
[1227/115932.328486:WARNING:resource_bundle_qt.cpp(115)] locale_file_path.empty() for locale 
[21861:21861:1227/115932.329840:FATAL:credentials.cc(155)] Check failed: NamespaceUtils::DenySetgroups(). : Permission denied
#0 0x7f0559e44aee <unknown>
#1 0x7f0559e570e2 <unknown>
#2 0x7f0559e5845c <unknown>
#3 0x7f055a9ccb21 <unknown>
#4 0x7f055a9cd2dd <unknown>
#5 0x7f0559a61527 <unknown>
#6 0x7f055970cd48 <unknown>
#7 0x7f0559710262 <unknown>
#8 0x7f05594fea9b <unknown>
#9 0x7f05594ffbd5 <unknown>
#10 0x7f05594eebdd <unknown>
#11 0x7f05594eef0e QtWebEngineCore::WebContentsAdapter::WebContentsAdapter()
#12 0x7f055f2cc091 <unknown>
#13 0x7f055f2ccc04 QWebEnginePage::QWebEnginePage() 
#14 0x7f055f2dbcfb QWebEngineView::page()
#15 0x564211f18a72 <unknown>
#16 0x564211f15872 <unknown>
#17 0x564211f00e36 <unknown>
#18 0x564211efb4d4 <unknown>
#19 0x7f0556336b97 __libc_start_main
#20 0x564211efbcaa <unknown>

Installed Qt WebEngine locales directory not found at location /usr/share/qt5/translations/qtwebengine_locales. Trying application directory...
Qt WebEngine locales directory not found at location /snap/kiwix-desktop/x3/usr/lib/x86_64-linux-gnu/qt5/libexec/qtwebengine_locales. Trying fallback directory... Translations MAY NOT not be correct.
Path override failed for key ui::DIR_LOCALES and path '/home/alan/snap/kiwix-desktop/x3/.QtWebEngineProcess'
Qt WebEngine resources not found at /usr/share/qt5/resources. Trying parent directory...
Qt WebEngine resources not found at /usr/share/qt5. Trying application directory...
Qt WebEngine resources not found at /snap/kiwix-desktop/x3/usr/lib/x86_64-linux-gnu/qt5/libexec. Trying fallback directory... The application MAY NOT work.
[1227/115932.477348:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.QtWebEngineProcess/qtwebengine_resources.pak
Some features may not be available.
[1227/115932.477427:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.QtWebEngineProcess/qtwebengine_resources_100p.pak
Some features may not be available.
[1227/115932.477440:ERROR:resource_bundle.cc(759)] Failed to load /home/alan/snap/kiwix-desktop/x3/.QtWebEngineProcess/qtwebengine_resources_200p.pak
Some features may not be available.
[1227/115932.478225:WARNING:resource_bundle_qt.cpp(115)] locale_file_path.empty() for locale 
[21585:21585:1227/115932.484461:FATAL:service_manager_context.cc(230)] Check failed: !contents.empty(). 
#0 0x7f0559e44aee <unknown>
#1 0x7f0559e570e2 <unknown>
#2 0x7f05599945bb <unknown>
#3 0x7f055970d9cb <unknown>
#4 0x7f055970ee83 <unknown>
#5 0x7f0559a219e9 <unknown>
#6 0x7f055970b01b <unknown>
#7 0x7f05597102dc <unknown>
#8 0x7f05594fea9b <unknown>
#9 0x7f05594ffbd5 <unknown>
#10 0x7f05594eebdd <unknown>
#11 0x7f05594eef0e QtWebEngineCore::WebContentsAdapter::WebContentsAdapter()
#12 0x7f055f2cc091 <unknown>
#13 0x7f055f2ccc04 QWebEnginePage::QWebEnginePage() 
#14 0x7f055f2dbcfb QWebEngineView::page()
#15 0x564211f18a72 <unknown>
#16 0x564211f15872 <unknown>
#17 0x564211f00e36 <unknown>
#18 0x564211efb4d4 <unknown>
#19 0x7f0556336b97 __libc_start_main
#20 0x564211efbcaa <unknown>

Aborted (core dumped)

```
