## Bitcoin Mining ဆိုတာ ဘာလဲ... Proof of Work, Mining Pool နဲ့ Reward ဘယ်လိုဆက်စပ်နေလဲ?

Cryptocurrency Mining အကြောင်းကို ဆက်လေ့လာရင်းနဲ့ ကျွန်တော် ပိုပြီးနားလည်လာတာက... Mining ဆိုတာ Bitcoin ကို "တူးဖော်" တာတစ်ခုတည်း မဟုတ်ဘဲ Blockchain ရဲ့ Security, Computing Power, Hardware နဲ့ Economic Incentive တွေ အားလုံးနဲ့ ဆက်စပ်နေတဲ့ Process တစ်ခုဖြစ်တယ်ဆိုတာပါ။

Bitcoin ရဲ့ အစောပိုင်းကာလမှာ Mining လုပ်တဲ့သူတွေ နည်းပါးတဲ့အတွက် Competition လည်း နည်းခဲ့ပါတယ်။ အဲဒီအချိန်မှာ သာမန် Computer တွေနဲ့တောင် Bitcoin Mining လုပ်နိုင်ခဲ့ပါတယ်။

ဒါပေမယ့် Bitcoin ကို စိတ်ဝင်စားပြီး Mining လုပ်တဲ့သူတွေ များလာတာနဲ့အမျှ Competition တိုးလာပြီး Computing Power ပိုလိုအပ်လာပါတယ်။

အဲဒီနောက်မှာ GPU တွေလို ပိုပြီး Powerful ဖြစ်တဲ့ Hardware တွေကို အသုံးပြုလာကြပြီး... နောက်ပိုင်းမှာတော့ Bitcoin Mining အတွက် အထူးပြုထုတ်လုပ်ထားတဲ့ Specialized Mining Hardware တွေ၊ ဥပမာ **Bitmain Antminer** လို ASIC Miner တွေ ပေါ်လာပါတယ်။

ဒီလိုနဲ့ Mining ဟာ Computer တစ်လုံးနဲ့ တစ်ယောက်တည်းလုပ်တဲ့အရာကနေ... Computing Power အများကြီးလိုအပ်တဲ့ လုပ်ငန်းတစ်ခုလို ဖြစ်လာပါတယ်။

### Mining Pool ဆိုတာ ဘာလဲ?

Mining လုပ်တဲ့သူတွေ များလာတာနဲ့အမျှ Miner တစ်ယောက်တည်းရဲ့ Computing Power နဲ့ Block Reward ရရှိဖို့ ပိုမိုမတည်ငြိမ်လာနိုင်ပါတယ်။

အဲဒီအတွက် Miners တွေက သူတို့ရဲ့ **Hash Power** တွေကို စုစည်းပြီး **Mining Pool** တွေထဲမှာ အတူတကွ Mining လုပ်လာကြပါတယ်။

အလွယ်နားလည်အောင်...

```text
Miner A ─┐
Miner B ─┤
Miner C ─┼──→ Mining Pool
Miner D ─┤
Miner E ─┘
            ↓
     Combined Hash Power
            ↓
       Bitcoin Mining
            ↓
        Block Reward
            ↓
       Payout Sharing
```

Mining Pool ရဲ့ အဓိကအကျိုးကျေးဇူးက... Miner တစ်ယောက်တည်း Mining လုပ်တဲ့အခါ Reward ရမယ့်အချိန် မတည်ငြိမ်နိုင်ပေမယ့် Pool ထဲမှာ အတူတကွ Mining လုပ်တဲ့အခါ Payout ကို ပိုမိုတည်ငြိမ်ပြီး ခန့်မှန်းရလွယ်အောင် ကူညီပေးနိုင်တာပါ။

ဒါပေမယ့်...

**Mining Pool ≠ Free Bitcoin**

Mining Pool ထဲဝင်တာနဲ့ Bitcoin အခမဲ့ရတာ မဟုတ်ပါဘူး။

ကိုယ်ပိုင် **Mining Hardware** ရှိဖို့လိုပြီး... Mining Software နဲ့ Bitcoin Wallet လည်း လိုအပ်ပါတယ်။

Mining Hardware ကနေ Mining Software ကိုအသုံးပြုပြီး Pool နဲ့ ချိတ်ဆက်ကာ ကိုယ်ပိုင် Hash Power ကို ပါဝင်စေပြီး... Pool ရဲ့ Payout System အတိုင်း Reward ကို ရရှိတာဖြစ်ပါတယ်။

Mining Pool အကြောင်းကို Bitbo မှာလည်း ဆက်လေ့လာနိုင်ပါတယ်...

[Bitcoin Mining Pool... Bitbo.io](https://bitbo.io/glossary/mining-pool/)

### Proof of Work...

Mining ရဲ့ အဓိကအကြောင်းအရာက Hardware တစ်ခုတည်း မဟုတ်ပါဘူး။

Bitcoin ရဲ့ Blockchain ကို ဆက်လက်လည်ပတ်ပြီး Security ကို ထောက်ပံ့ပေးတဲ့ Process ထဲမှာ **Proof of Work** က အရေးကြီးတဲ့ အစိတ်အပိုင်းတစ်ခုဖြစ်ပါတယ်။

Miner တွေဟာ Computational Work လုပ်ပြီး Block တစ်ခုကို Blockchain ထဲ ထည့်နိုင်ဖို့ လိုအပ်တဲ့ Proof of Work ကို ရှာဖွေကြပါတယ်။

အရင်က ကျွန်တော်လေ့လာခဲ့တဲ့ **SHA-256 Hashing** ကလည်း ဒီနေရာမှာ ပြန်ပြီး ဆက်စပ်လာပါတယ်။

အလွယ်နားလည်အောင်...

```text
Block Information
        ↓
SHA-256 based Hashing
        ↓
Target နဲ့ ကိုက်ညီလား?
        ↓
မကိုက်သေးရင် Nonce စတာတွေ ပြောင်း
        ↓
Hash ပြန်တွက်
        ↓
Valid Proof of Work
        ↓
Block Process
```

ဒီနေရာမှာ "Hash ကို decrypt လုပ်တာ" ဒါမှမဟုတ် "Code ကို crack လုပ်တာ" လို့ မမှတ်သင့်ပါဘူး။

Mining မှာ သတ်မှတ်ထားတဲ့ Target နဲ့ ကိုက်ညီတဲ့ Hash ရလာအောင် Block Header information တွေထဲက Nonce စတဲ့ တန်ဖိုးတွေကို ပြောင်းပြီး Hash တွေကို အကြိမ်ကြိမ်တွက်ကြတာဖြစ်ပါတယ်။

အဲဒီကနေ Blockchain နဲ့ Mining ဘယ်လိုဆက်စပ်နေသလဲဆိုတာ ပိုပြီးရှင်းလာပါတယ်။

```text
Transactions
      ↓
    Block
      ↓
Proof of Work
      ↓
 Blockchain
      ↓
  Next Block
```

Block တစ်ခုနဲ့တစ်ခုလည်း သီးခြားစီ ရှိနေတာမဟုတ်ပါဘူး။

```text
Genesis Block
      ↓
   Block 2
      ↓
   Block 3
      ↓
   Block 4
      ↓
     ...
```

Block တစ်ခုစီက အရင် Block ကို Reference လုပ်ထားတဲ့အတွက် Blockchain တစ်ခုလုံးဟာ Chain တစ်ခုလို ဆက်စပ်နေပါတယ်။

### Block Reward, Halving နဲ့ Transaction Fees

Mining လုပ်ပြီး Block တစ်ခုကို အောင်မြင်စွာ ထည့်သွင်းနိုင်တဲ့အခါ Miner အတွက် **Block Reward** ရရှိနိုင်ပါတယ်။

Bitcoin ရဲ့ အစောပိုင်းကာလမှာ Block Subsidy က ပိုများခဲ့ပေမယ့်... အချိန်ကြာလာတာနဲ့အမျှ Reward ကို အဆင့်ဆင့် လျှော့ချလာပါတယ်။

Bitcoin ရဲ့ Block Subsidy ဟာ သမိုင်းတစ်လျှောက်...

**50 BTC → 25 BTC → 12.5 BTC...**

လိုမျိုး လျော့လာခဲ့ပြီး... ခန့်မှန်းအားဖြင့် **210,000 blocks တိုင်း Reward ကို တစ်ဝက်စီ လျှော့ချတဲ့ Halving** စနစ်ရှိပါတယ်။

Reward က တဖြည်းဖြည်း လျော့လာတဲ့အတွက် နောက်ပိုင်းမှာ Miner တွေရဲ့ Revenue ထဲမှာ **Transaction Fees** ကလည်း အရေးကြီးတဲ့ အစိတ်အပိုင်းတစ်ခု ဖြစ်လာပါတယ်။

အလွယ်နားလည်အောင်...

```text
Proof of Work
      ↓
Valid Block
      ↓
Block Subsidy
      +
Transaction Fees
      ↓
Miner Revenue
```

ဆိုတဲ့ ဆက်စပ်မှုနဲ့ မှတ်ထားလို့ရပါတယ်။

### Bitcoin Supply နဲ့ Satoshi

ဒီနေရာကနေ Bitcoin ရဲ့ Supply အကြောင်းကိုလည်း ဆက်စပ်ပြီး စဉ်းစားလို့ရပါတယ်။

Bitcoin ရဲ့ **Maximum Supply က 21 million BTC** ဖြစ်ပါတယ်။

ဆိုလိုတာက... Bitcoin အားလုံးပေါင်းပြီး ဖန်တီးနိုင်မယ့် ပမာဏဟာ **21 million BTC ထက် မပိုပါဘူး။**

ဒါပေမယ့် Bitcoin တစ်ခုလုံးကိုပဲ ပိုင်ဆိုင်ဖို့ မလိုပါဘူး။

**1 BTC ကို 100 million အထိ ခွဲနိုင်ပြီး... အဲဒီအငယ်ဆုံး unit ကို Satoshi လို့ခေါ်ပါတယ်။**

```text
1 BTC
   ↓
100,000,000 Satoshi

1 Satoshi
   =
0.00000001 BTC
```

ဒါကြောင့် Bitcoin ရဲ့ Supply က 21 million BTC အထိ ကန့်သတ်ထားပေမယ့်... Bitcoin ကို အသုံးပြုတဲ့အခါမှာတော့ BTC တစ်ခုလုံးအထိ ပိုင်ဆိုင်ဖို့ မလိုဘဲ အလွန်သေးငယ်တဲ့ အစိတ်အပိုင်းအထိ အသုံးပြုနိုင်ပါတယ်။

### Mining Pool ရဲ့ နောက်ထပ်စိတ်ဝင်စားစရာ...

Mining Pool တွေမှာ **Fees** နဲ့ **Payout Methods** တွေလည်း မတူကြပါဘူး။

ဥပမာ Bitbo ရဲ့ Mining Pool comparison မှာ Foundry USA, Antpool, F2Pool, ViaBTC, Binance Pool, Luxor, Braiins Pool စတဲ့ Pool တွေကို ဖော်ပြထားပြီး... Pool တစ်ခုချင်းစီရဲ့ Fee နဲ့ Payout Method တွေ မတူတာကို တွေ့ရပါတယ်။

Payout Method တွေထဲမှာ...

**PPS (Pay Per Share)**
**PPLNS (Pay Per Last N Shares)**
**FPPS (Full Pay Per Share)**

စတာတွေရှိပါတယ်။

ဒီ Payout Method တွေဟာ Miner တွေရဲ့ Contribution နဲ့ Pool က Reward ကို ဘယ်လိုတွက်ပြီး ဖြန့်ဝေပေးမလဲဆိုတာနဲ့ ဆက်စပ်ပါတယ်။

ဒါကြောင့် Mining Pool ကို လေ့လာတဲ့အခါ Pool တစ်ခုချင်းစီရဲ့ **Fee, Payout Method, Minimum Payout, Supported Hardware/Software** စတာတွေကိုလည်း သီးခြားလေ့လာဖို့ လိုလာပါတယ်။

အခု Mining အကြောင်းကို ဆက်လေ့လာရင်း ကျွန်တော် သတိထားမိတာတစ်ခုက...

Mining ဟာ Blockchain, Hashing, Proof of Work, Hardware နဲ့ Economic Incentive တွေကို သီးခြားစီ လေ့လာထားတာထက်... အားလုံးကို တစ်ဆက်တည်း ချိတ်ဆက်ပေးနေတဲ့ အပိုင်းတစ်ခုဖြစ်တယ်ဆိုတာပါ။

**Blockchain → Hashing → Proof of Work → Mining → Hardware → Mining Pool → Block Reward → Halving → Transaction Fees**

ဒီ Flow ကို နားလည်ထားရင် Mining အကြောင်းကို နောက်ထပ် ဆက်လေ့လာတဲ့အခါ ပိုပြီးလွယ်လာမယ်လို့ ကျွန်တော် နားလည်လာပါတယ်။

### နောက်တစ်ဆင့်...

အခုဆိုရင် ဒီ Mining Lecture ရဲ့ နောက်တစ်ဆင့်ကို ရောက်လာပါပြီ။

နောက်ပိုင်းမှာ **Bitmain Antminer ကို ကိုယ်တိုင်ဖြုတ်ပြီး အတွင်းမှာ ဘာတွေပါလဲဆိုတာ လေ့လာမယ်... ပြီးရင် Mining Computer တစ်လုံးကို Components တွေကနေ Scratch ကနေ ကိုယ်တိုင်တည်ဆောက်တာကို ဆက်လေ့လာသွားပါမယ်။**

ကျွန်တော်ကတော့ Beginner တစ်ယောက်အနေနဲ့ Course ကို လေ့လာရင်း နားလည်လာတာတွေကို ကိုယ်တိုင်ပြန်ရေး၊ လက်တွေ့နဲ့ ဆက်စပ်ပြီး ပြန်လည်မျှဝေပေးတာဖြစ်ပါတယ်။

**Learn → Understand → Practice → Research → Share**

### ဆက်လေ့လာချင်သူများအတွက်...

ကျွန်တော်က ဒီ Course ကို လေ့လာရင်း နားလည်လာတဲ့ **Notes တွေ၊ Exercises တွေ၊ လက်တွေ့လုပ်ဆောင်ထားတာတွေကို** တစ်နေရာတည်းမှာ စနစ်တကျ စုစည်းထားချင်တာကြောင့် GitHub Repository တစ်ခုထဲမှာ ဆက်လက်တည်ဆောက်နေပါတယ်။

နောက်ပိုင်းမှာ Cryptocurrency, Bitcoin, Blockchain, Wallet, Security နဲ့ အခြားဆက်စပ်တဲ့အကြောင်းအရာတွေကို ဆက်ပြီးလေ့လာချင်တယ်ဆိုရင်... ဒီ Repository မှာ အစကနေ တစ်ဆင့်ချင်း ဆက်လေ့လာနိုင်ပါတယ်။

**GitHub Repository:**
[Crypto Course (Myanmar) ... GitHub Repository](https://github.com/wzhtoo/crypto)

ကျွန်တော်ကိုယ်တိုင်လည်း Beginner တစ်ယောက်အနေနဲ့ လေ့လာရင်း နားလည်လာတာတွေကို ပြန်ရေး၊ လက်တွေ့စမ်းပြီး တဖြည်းဖြည်း စုစည်းသွားမှာဖြစ်ပါတယ်။

**Learn → Understand → Practice → Research → Share**
