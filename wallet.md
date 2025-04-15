<style>
.md0{padding-bottom: 150px;}
.md1{padding-bottom: 75px;}
.md2{padding-bottom: 50px;}
.md3{padding-bottom: 25px;}
.md4{padding-bottom: 5px;}
.md5{padding-bottom: 10px;}
.a{display: inline-block;width: 50px;background-color: white}
.b{display: inline-block;width: 150px;background-color: white}
.c{display: inline-block;width: 450px;background-color: white}
.d{display: inline-block;width: 400px;background-color: white}
.tbl1 td#header{background-color: D1ECCF}
.tbl1 tr#header{background-color: D1ECCF}
.red{color:#E74C3C}
.blue{color:#3498DB}
.green{color:#28B463}
table{border: 0px solid black;}
.child {display:inline-block;vertical-align: top;margin-right: 10px;}
</style>

# [<span style="color:black;">Wallet</span>](../index.md) 

[Economy](economy.md) |
[Technology](technology.md) |
[Forex](forex.md) |
[Crypto](crypto.md) |
[Mining](mining.md) |
[Wallet](wallet.md) |
[Techniqual](techniqual.md) |
[Project](project.md) |
[Analysis](analysis.md) |
[Strategy](strategy.md) |
[Execution](execution.md) |
[Data](data.md) |
[Develop](develop.md) |
[Resource](resource.md)

<div align="left"><img src="diagram/wallet.jpeg"></div>

<div class="md3">
<a href="#diagram">Diagram</a> - 
<a href="#concept">Concept</a> -
<a href="#type">Type</a> -
<a href="#proof">Proof</a> -
<a href="#wallet-1">Wallet</a> - 
<a href="#note">Note</a>
</div>



<!-----------------------------------------------------------Concept----------------------------------------------------------->
<div class="md5"></div>

## Concept

<div class="" align="right" dir="rtl">
<div class="md4">۱ - کیف پول در واقع یک جفت کلید است که میتونی باهاش اطلاعات رو رمز کنی  و همچنین امضا کنی</div>
<div class="md4">۲ - وقتی یکی میخواد به شما پول بده میره تو بلاک چین مینویسه این مقدار پول برای این آدرس (کلید عمومی جفت کلید شما) است</div>
<div class="md4">۳ - وقتی شما میخوای به یکی پول بدی باید بری تو بلاک چین بنویسی اینقدر پول مال فلانیه و نوشته خودت را امضا کنی که همه بفهمن خودت نوشتی که این کار با (کلید خصوصی جفت کلید شما) انجام میشود </div>
<div class="md4">۴ - مردم چون (کلید عمومی جفت کلید شما) دارند و همچنین امضا رو دارن پس میتونن بررسی کنن این امضا با این آدرس عمومی مطابقت دارد یا نه و اگه مطابقت داشته باشه یعنی این جمله اعتبار دارد چون کسی میتونه امضا کنه که کلید خصوصی جفت ارز رو داشته باشه</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>



<!-----------------------------------------------------------Type----------------------------------------------------------->
<div class="md1"></div>

## Type

<!--------------------------------------Custodial Wallet-->
#### <span class="red">Custodial Wallet</span>
<div class="" align="right" dir="rtl">
<div class="md4">کیف پول هایی که Private-Key رو پیش خودشون نگه میدارن و به شما نمیدن</div>
</div>

<!--------------------------------------Non-Custodial Wallet-->
#### <span class="red">Non-Custodial Wallet</span>
<div class="" align="right" dir="rtl">
<div class="md4">کیف پول هایی که Private-Key رو پیش خودشون نگه نمیدارن و در اختیار شما قرار میدهند</div>
<div class="md4">Trust Wallet | Atomic Wallet</div>
</div>

<!--------------------------------------Hot Wallet-->
#### <span class="red">Hot Wallet</span>
<div class="" align="right" dir="rtl">
<div class="md4">کیف پول های نرم افزاری که همیشه روی یک سرور هستند و در معرض اینترنت هستند</div>
</div>
<div class="" align="left" dir="ltr">
<div class="md4"><span class="blue">Project</span> : <span>Project : Trust Wallet | Metamask | Exodus | Atomic Wallet | Coinomi | Myetherwallet | Bluewallet | Math Wallet</span></div>
</div>

<!--------------------------------------Cold Wallet-->
#### <span class="red">Cold Wallet</span>
<div class="" align="right" dir="rtl">
<div class="md4">کیف پول های سخت افزاری که در معرض اینترنت نیستند</div>
</div>
<div class="" align="left" dir="ltr">
<div class="md4"><span class="blue">Paper Wallet</span> : <span>BitAdress</span></div>
<div class="md4"><span class="blue">Hardware Wallet</span> : <span>Ledger, Trezor hd wallet</span></div>
</div>



<!-----------------------------------------------------------Proof----------------------------------------------------------->
<div class="md1"></div>

## Proof

<!--------------------------------------Proof of Liabilities-->
#### <span class="red">Proof of Liabilities</span>
<div class="" align="right" dir="rtl">
<div class="md4">از کجا بفهمیم چه قدر پول از مشتریها در اختیار این Wallet هست ؟ با استفاده از روش Merkle tree</div>
</div>

<!--------------------------------------Proof of Reserve-->
#### <span class="red">Proof of Reserve</span>
<div class="" align="right" dir="rtl">
<div class="md4">یک Wallet آنلاین چگونه می‌تونه ثابت کنه که به چقدر از پول هایی که بهش دادیم الان دسترسی داره؟</div>
<div class="md4">می‌تونه از یک Wallet به یک Wallet دیگر پول انتقال بده تا اطمینان حاصل بشه که دسترسی‌ به این مقدار پول دارد</div>
<div class="md4">می‌تونه برای اطمینان بیشتر، به TRX یه Nonce هم اضافه کنه که همه بفهمن واقعا خودش این کار رو انجام داده</div>
</div>



<!-----------------------------------------------------------Wallet----------------------------------------------------------->
<div class="md1"></div>

## Wallet

<!---------------------------------------AAA-->
#### <span class="red">Metamask</span>

<div class="md4">
<span class="blue">Type</span> : <span class="b">Hot Wallet</span>
<span class="blue">Custody</span> : <span class="b">Non-custodial</span>
<span class="blue">Founder</span> : <span class="b"></span>
<span class="blue">Start</span> : <span class="a"></span>
<span class="blue">Rate</span> : <span>A</span>
</div>
<div class="md4"><span class="blue">Support</span> : <span>Ethereum (ERC20) | Binance Smart Chain (BSC) | Polygon (MATIC)</span></div>
<div class="md4"><span class="blue">Techniqual</span> : <span>Open Source | Chrom Extension</span></div>
<div class="md4"><span class="blue">Tag</span> : <span class="c"></span></div>
<div class="md4"><span class="blue">Partnership</span> : <span></span></div>
<div class="md4"><span class="blue">Same</span> : <span></span></div>
</div>
<div class="" align="right" dir="rtl">
<div class="md4">هنوز هیچ توکنی ندارد</div>
<div class="md4">همه چی سمت کاربر انجام میشه</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>



<!-----------------------------------------------------------Note----------------------------------------------------------->
<div class="md1"></div>

## Note

<div class="" align="right" dir="rtl">
<div class="md4">Open Source : Metamask | WASABI</div>
<div class="md4">Hardware : Ledger Nano S</div>
<div class="md4">Other : coinomi | Exodus | WASABI | Atomic Wallet | Rabinhood | Electrum | Coinbase Wallet | Trustwallet | Freewallet | Trezor | Mycelium | Jaxx | Bread Wallet</div>

<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>