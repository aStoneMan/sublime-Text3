# sublime-Text3
how to install a sublime Text3 for PHPer
<br />first,Ctrl+`  we get console.
<br />give this code to sublime
<br />import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
<br />restart your sublime
<br />and you could install
<br />emmet
<br />IMESupport
<br />SublimeLinter
<br />Bracket Highlighter
