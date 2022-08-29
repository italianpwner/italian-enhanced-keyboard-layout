# italian-enhanced-keyboard-layout
The keyboard layout I personally use as an Italian programmer.

It is a customization of [Windows' Italian keyboard layout](https://kbdlayout.info/KBDIT/) (KLID: *00000410*) which supports the following extra characters:

| Key combination   | Char | VK code  | Unicode | Description                       |
|------------------:|:----:|:---------|:-------:|:----------------------------------|
| Shift + AltGr + e | È    | VK_E     | U+00C8  | LATIN CAPITAL LETTER E WITH GRAVE |
| AltGr + '         | `    | VK_OEM_4 | U+0060  | GRAVE ACCENT (backtick)           |
| AltGr + ì         | ~    | VK_OEM_6 | U+007E  | TILDE                             |
| AltGr + c         | ©    | VK_C     | U+00A9  | COPYRIGHT SIGN                    |
| AltGr + r         | ®    | VK_R     | U+00AE  | REGISTERED SIGN                   |
| AltGr + t         | ™    | VK_T     | U+2122  | TRADE MARK SIGN                   |

I've used [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) (MSKLC) to edit the layout's "source code" (file: *layout.klc*), to generate its setup executable and build its DLLs. 
