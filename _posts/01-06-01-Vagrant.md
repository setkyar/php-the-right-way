---
isChild: true
anchor: vagrant
---

## Vagrant {#vagrant_title}


တကယ်လို့သာ သင့်ရဲ့ application ကို ကွဲပြားလှတဲ့ enivornment များ run ဖူးရင် ဘယ်လိုရှင်းရမှန်းမသိတဲ့ ထူးဆန်းအံဩဖွယ်ရာ bugs တွေကို တွေ့ရမှာ ဖြစ်ပါတယ်။ တကယ်လို့သာ team နဲ့ အလုပ်လုပ်တဲ့ အခါက မတူညီတဲ့ developer တွေရဲ့ environment ပေါ်မူတည်ပြီး libraries တွေရဲ့ version ကို maintain လုပ်ရတာ ခက်ခဲပါတယ်။ 

တကယ်လို့သင်က Windows ပေါ်က develop လုပ်နေပြီး Linux ဒါမှမဟုတ် Window မဟုတ်တဲ့ OS တစ်ခုခုကို deploy လုပ်တာဖြစ်ဖြစ် ၊ team အနေနဲ့အလုပ်လုပ်ရင်ဖြစ်ဖြစ် virtual machine တစ်ခုခုကို အသုံးပြုဖို့ စဉ်းစားသင့်ပါတယ်။ ကြားရတာ ရှုပ်ထွေးပေမယ့် တကယ်တမ်း [Vagrant][vagrant]
ကိုအသုံးပြုပြီး သင့်အနေနဲ့ လွယ်ကူရှင်းလင်းတဲ့ virtual machine တစ်ခုကို အဆင့်အနည်းငယ်တွင်းမှာ ဖန်တီးနိုင်ပါတယ်။ ထို အခြေခံ Box များကို manually ဖြစ်စေ ၊ [Puppet][puppet] နှင့် [Chef][chef] တို့ကို အသုံးပြုပြီး အလွယ်တကူ ဖန်တီးနိုင်ပါတယ်။ ထိုသို့ပြုလုပ်ခြင်းအားဖြင့် Box များစွာ တူညီစွာတည်ရှိမှာ ဖြစ်ပြီးတော့ သင့်အနေနဲ့ ရှုပ်ထွေးလှတဲ့  "set up" command များကို မှတ်မိစရာမလိုတော့ပါဘူး။ အသုံးမပြုလိုပါကလည်း အလွယ်တကူ ဖျက်ပစ်နိုင်သလို ပြန်၍ ဖန်တီးချင်ရင်လည်း မခက်ခဲလှပါဘူး။ 

Vagrant အနေနဲ့ Host နဲ့ Virtual Machine အကြား share လုပ်ပေးတဲ့ folders များဖန်တီးပေးတဲ့အတွက် host machine များ file များ ဖန်တီး ၊ ပြင်ဆင် နိုင်ပြီး virtual machine တွင် ပြန်ပြီး run နိုင်ပါသည်။ 


### အကူအညီ

သင့်အနေနဲ့ Vagrant အသုံးပြုရမှာ မရင်းနှီးပါက အောက်ပါလင့်များကို ဖတ်ရှုနိုင်ပါသည်။ 

- [Rove][rove]: Vagrant builds များကို Chef ကိုအသုံးပြု၍ ကြိုပြီးထုတ်နိုင်ပြီး ရွေးချယ်စရာများတွင် PHP လည်းပါဝင်သည်။ 
- [Puphpet][puphpet]: PHP development အတွက် virutal machine များကို GUI မှတစ်ဆင့် ရွေးချယ် set up ပြုလုပ်နိုင်သည်။ **PHP ကို အဓိကထားထားပြီး**
local VMs များကို cloud service များတွင် deploy လုပ်နိုင်သည်။ 
- [Protobox][protobox]: GUI ကိုအသုံးပြု၍ vagrant အခြေပြု virtual machine များကို ဖန်တီးနိုင်သည်။ virtual machine တွင် ပြုလုပ်လိုသည်များကို YAML document တစ်ခုတည်းဖြင့်သာ ထိန်းချုပ်နိုင်သည်။ 

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
[rove]: http://rove.io/
[puphpet]: https://puphpet.com/
[protobox]: http://getprotobox.com/
