# sublime-Text3
how to install a sublime Text3 for PHPer
first,Ctrl+`  we get console.
give this code to sublime
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
restart your sublime
and you could install
emmet
IMESupport
SublimeLinter
Bracket Highlighter
