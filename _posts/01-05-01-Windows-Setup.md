---
isChild: true
anchor: windows_setup
---

## Windows Setup {#windows_setup_title}

PHP က Window မှာနည်းမျိုးစုံနဲ့ install လုပ်နိုင်ပါတယ်။ သင့်အနေဲ့ [PHP Binaries ][php-downloads] ကို download လုပ်ပြီး setup လုပ်တာဖြစ်ဖြစ် ဒါမှမဟုတ်လည်း  '.msi' installer နဲ့လည်းလုပ်နိုင်ပါတယ်။ သို့သော် installer support လုပ်တာကို PHP 5.3.0 မှာ ရပ်လိုက်ပါပြီ။

သင့်အနေနဲ့ PHP 5.4 နဲ့အထက်မှာ build in webserver ပါဝင်လာပြီး configuration အတွက်ဘာမှမပူဘဲနဲ့ လေ့လာဖို့ရန်အတွက်နဲ့ local developement အတွက်အသုံးပြုနိုင်ပါတယ်။ သင့်အနေနဲ့ webserver နဲ့ MySQL ပါပါတဲ့ "all-in-one" installer တွေကိုသုံးပြီး install လုပ်ချင်တယ်ဆိုရင်တော့ [Web Platform Installer][wpi], 
[Zend Server CE][zsce], [XAMPP][xampp], [EasyPHP][easyphp] နဲ့ [WAMP][wamp] software တွေက window development ကိုလျှင်မြန်စွာ setup လုပ်ပေးပါလိမ့်မယ်။ သတိပြုရန်မှာ အဲ့ဒီ tools တွေက production နဲ့မတူညီတဲ့အတွက် သင်က window မှာ develop လုပ်ပြီး linux မှာ deploy လုပ်ရင် environment setup ကိုတော့ ဂရုစိုက်ရပါ့မယ်။

သင့် Production က Window မှာဆိုရင် IIS7 က အကောင်းဆုံးဖြစ်ပါလိမ့်မယ်။ သင့်အနေနဲ့ PHP Configuration လွယ်ကူစွာ Manage လုပ်နိုင်ရန်အတွက် [phpmanager][phpmanager] (IIS7 အတွက် GUI plugin) ကိုအသုံးပြုနိုင်ပါတယ်။ သင့်အနေနဲ့ IIS7 မှာ PHP Handler တစ်ခုအနေနဲ့ configuration လုပ်ရုံသာ ဖြစ်ပါတယ်။ ဘာလို့လည်းဆိုရင် IIS7 မှာ FastCGI က built in ပါဝင်လို့ပါ။ PHP ကို IIS7 မှာ Install လုပ်ရာမှာ Support နဲ့အခြား resources တွေကိုတော့ [iis.net][php-iis] မှာကြည့်နိုင်ဖတ်နိုင်ပါတယ်။

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[easyphp]: http://www.easyphp.org/
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
