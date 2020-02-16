Use patch or keys (seems that not all keys work in the latest dev-builds) from sublime3_keys.txt.

Patch variants:
1 (regular). You will see* in the About:
Registered to
Unlimited User License

2 (with_PhoenixBBS_in_About). In the About will*:
Registered to
PhoenixBBS

In this case, you can open sublime_text.exe in hex-editor, find ANSI-string 'PhoenixBBS' (of course, without the quotes) and
replace it to your name (must contain only English characters and the length should be no more than 'Unlimited User License').

* Since build 3137, another method of cracking is used, with which, if it has a working license in "Data\Local\License.sublime_license"
(portable version) or somewhere in the %AppData%\Sublime Text... / %LocalAppData%\Sublime Text... (installed version, I do not remember
the exact location), then in About will be key data, not these. To display them, you must delete the file "License.sublime_license".

patch tested/works with ST3 x86/x64 builds 3103 - 3141 (perhaps, with the earlier ones too).

Credits:

crack x86: ManHunter/PCL
crack x64: Morsx @ru-board
new crack 3137+: pawel97
fix cracks x86/x64 for latest builds and made patch: addhaloka

Thanks to pawel97 for help and T3rM1nat0Rr3 for the reports.