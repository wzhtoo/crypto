# Blockchain မှာ Block တွေ ဘယ်လိုချိတ်ဆက်ထားသလဲ

Crypto နဲ့ Blockchain အကြောင်း ဆက်လက်လေ့လာရင်း ဒီတစ်ခါမှာ Blockchain ရဲ့ အခြေခံအလုပ်လုပ်ပုံကို ပိုပြီးနားလည်လာပါတယ်။

အစောပိုင်း မှာ Blockchain ကို Digital Ledger တစ်ခုအဖြစ် နားလည်ခဲ့ပါတယ်။ ဒီဒုတိယပိုင်းမှာတော့ Ledger ရဲ့ စာမျက်နှာတွေကို ဘယ်လို Block တွေအဖြစ် ပြောင်းလဲပြီး တစ်ခုနဲ့တစ်ခု ချိတ်ဆက်ထားသလဲဆိုတာ ဆက်လေ့လာခဲ့ပါတယ်။

## Block 1 → Block 2 → Block 3

Blockchain မှာ Block တစ်ခုစီက သူ့ရှေ့က Block ကို Reference လုပ်ထားပါတယ်။

Block 2 ထဲမှာ Block 1 ရဲ့ Hash ကို သိမ်းထားပါတယ်။ Block 3 ထဲမှာလည်း Block 2 ရဲ့ Hash ကို သိမ်းထားပါတယ်။

ဒီလိုချိတ်ဆက်ထားတဲ့အတွက် Blockchain ဟာ ရိုးရိုး Data တွေကို စုစည်းထားတဲ့ Database တစ်ခုထက်ပိုပြီး Chain တစ်ခုလို အလုပ်လုပ်ပါတယ်။

## SHA-256 Hash ရဲ့ အရေးပါမှု

Ledger ထဲက စာသားတွေကို SHA-256 နဲ့ Hash လုပ်လိုက်ရင် Character 64 လုံးပါဝင်တဲ့ Hash String တစ်ခု ရလာပါတယ်။

ဥပမာ...

```text
Original Data
     ↓
SHA-256 Hash
     ↓
64-character Hash
```

ဒီ Hash ကို နောက် Block မှာ သိမ်းထားပါတယ်။

တကယ်လို့ အရင် Block ထဲက Data တစ်ခုကို တိတ်တဆိတ်ပြင်လိုက်ရင် Hash ပြောင်းသွားနိုင်ပါတယ်။ အဲဒီအခါ နောက် Block ထဲမှာ သိမ်းထားတဲ့ Previous Hash နဲ့ မကိုက်တော့ပါဘူး။

ဒီအချက်က Blockchain ရဲ့ Tamper Detection နဲ့ Data Integrity အတွက် အရေးကြီးတဲ့အခြေခံတစ်ခု ဖြစ်ပါတယ်။

## Blockchain က ငွေလွှဲတာအတွက်ပဲ မဟုတ်ပါ

Blockchain ဆိုတာ Cryptocurrency တစ်ခုတည်းအတွက် အသုံးပြုတဲ့ Technology မဟုတ်ပါဘူး။

အနာဂတ်မှာ Election Data, Business Contracts, Sports Contracts, Car Lease Records, Historical Records နဲ့ အခြား Digital Information တွေကိုလည်း Blockchain နဲ့ စီမံနိုင်မယ့် အယူအဆတွေ ရှိပါတယ်။

ဒါပေမယ့် Blockchain ထည့်လိုက်ရုံနဲ့ System တစ်ခုလုံး လုံခြုံသွားမယ်လို့တော့ မယူဆသင့်ပါဘူး။ Privacy, Scalability, Governance, Access Control နဲ့ Data Quality တွေကိုလည်း သေချာစဉ်းစားဖို့ လိုပါတယ်။

## Permanent ဆိုတာ ဘာလဲ

Blockchain Transaction တွေဟာ Permanent ဖြစ်တယ်လို့ ရှင်းပြထားပါတယ်။

နည်းပညာအရတော့ Confirmed Data ကို ပြန်ပြင်ဖို့ အလွန်ခက်ခဲတယ်လို့ နားလည်ရင် ပိုမှန်ကန်မယ်ထင်ပါတယ်။

Blockchain ကို Distributed Network ပေါ်မှာ Node အများအပြားက သိမ်းထားတဲ့အတွက် Server တစ်လုံးပျက်သွားတာနဲ့ Ledger တစ်ခုလုံး ပျောက်ဆုံးသွားဖို့ မလွယ်ကူပါဘူး။

ဒါပေမယ့် Blockchain ဟာ လုံးဝ Attack-Proof ဖြစ်တယ်၊ ဘယ်လိုအခြေအနေမျိုးမှာမဆို မပြင်နိုင်ဘူးလို့တော့ မယူဆသင့်ပါဘူး။

## Bitcoin Block Time

Bitcoin Network မှာ Block အသစ်တစ်ခုကို ပျမ်းမျှအားဖြင့် ၁၀ မိနစ်ခန့်တိုင်း ထုတ်လုပ်ပါတယ်။

ဒီနေရာမှာ စိတ်ဝင်စားစရာကောင်းတာက Transaction ပိုများလာတာနဲ့ Block Time တိုက်ရိုက်လျော့သွားတာ မဟုတ်ပါဘူး။ Bitcoin ရဲ့ Mining Difficulty Adjustment က ပျမ်းမျှ Block Time ကို ၁၀ မိနစ်ခန့် ဖြစ်အောင် ထိန်းညှိပေးပါတယ်။

2015 ခုနှစ်က Block တစ်ခုမှာ Block Reward 25 BTC ရှိခဲ့ကြောင်း Lecture မှာ လေ့လာခဲ့ရပါတယ်။ အချိန်ကြာလာတာနဲ့အမျှ Block Reward Halving ဖြစ်စဉ်ကြောင့် Reward ပမာဏက လျော့ကျလာပါတယ်။

ဒီအပိုင်းကို လေ့လာပြီးတဲ့နောက် Blockchain ဆိုတာ ငွေကြေးလွှဲပြောင်းမှုအတွက်ပဲ မဟုတ်ဘဲ Data Integrity, Transparency, Distributed Storage နဲ့ Digital Record Management အတွက်ပါ အရေးကြီးတဲ့ Technology တစ်ခုဖြစ်ကြောင်း ပိုပြီးနားလည်လာပါတယ်။

ကျွန်တော်ကတော့ ဆက်လက်လေ့လာရင်း သိလာသမျှကို Beginner တစ်ယောက်ရဲ့ အမြင်နဲ့ ပြန်လည်မျှဝေသွားပါမယ်။

**Learn → Try → Observe → Understand → Share**

မှတ်ချက်။ ဒီပို့စ်ဟာ ပညာပေးလေ့လာမှုအတွက်သာ ဖြစ်ပြီး Cryptocurrency ဝယ်ယူရန်၊ ရောင်းချရန် သို့မဟုတ် ရင်းနှီးမြှုပ်နှံရန် အကြံပြုချက်မဟုတ်ပါ။
