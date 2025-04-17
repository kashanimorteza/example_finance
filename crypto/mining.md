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

# [<span style="color:black;">Mining</span>](../index.md) 

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

<div align="left"><img src="diagram/mining.jpeg"></div>

<div class="md3">
<a href="#diagram">Diagram</a> - 
<a href="#concept">Concept</a> -
<a href="#consensus">Consensus</a> -
<a href="#devices">Devices</a> -
<a href="#pool">Pool</a> -
<a href="#note">Note</a>
</div>



<!-----------------------------------------------------------Concept----------------------------------------------------------->
<div class="md5"></div>

## Concept

<div class="" align="right" dir="rtl">
<div class="md4">1 - یه سری آدم دارن پول انتقال میدان، که مثلا چه مقدار پول از کجا به کجا انتقال پیدا کند، به اینها میگن Transaction = TRX</div>
<div class="md4">2 - تراکنشهای جدید به تمامی نودها مخابره میشوند</div>
<div class="md4">3 -  ماینر ها تراکنشها را میگیرند و در MemPool خود ذخیره می کنند </div>
<div class="md4">4 - Trx مخصوص که مشخص کننده جایزه ماینر هست را هم اضافه می کند</div>
<div class="md4">5 - یک Nonce هم اضافه می کند</div>
<div class="md4">6 - Hash بلاک قبلی‌ رو هم اضافه می‌کند</div>
<div class="md4">7 - Hash این مجموعه اطلاعات رو حساب می کند</div>
<div class="md4">8 - Hash ساخته شده را با قانون POW بررسی می کند</div>
<div class="md4">9 - اگر طبق اون قانون نبود، Nonce را عوض می کند و دوباره Hash را حساب می کند</div>
<div class="md4">10 - اگر طبق اون قانون بود، او برنده شده است و اون مقدار جایزه برای او خواهد شد و به شبکه اعلام می کند</div>
<div class="md4">11 - سایر نودها بلوک مذکور را تنها در شرایطی میپذیرند که کل تراکنشهای آن صحیح با شند و قبلا خرج نشده باشند</div>
<div class="md4">12 - سایر نودها موافقت خود را با بلوک مورد نظر با ایجاد بلوک بعدی در زنجیره اعلام میدارند و بهاین منظور از هش بلوک پذیرفته شده به عنوان هش قبلی استفاده میکنند</div>
<div class="md4">Nonce</div>
<div class="md4">Difficulty</div>
<div class="md4">Reward</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!-----------------------------------------------------------Consensus----------------------------------------------------------->
<div class="md1"></div>

## Consensus

<div class="" align="right" dir="rtl">
<div class="md4">سازکار و روشهایی برای اعتماد و به توافق رسیدن افراد فعال داخل شبکه</div>
</div>

<!--------------------------------------POW (Proof of Work)-->
#### <span class="red">POW (Proof of Work)</span>
<div class="" align="right" dir="rtl">
<div class="md4">انرژی زیاد مصرف میکنه</div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------POS (Proof of Stake)-->
#### <span class="red">POS (Proof of Stake)</span>
<div class="" align="right" dir="rtl">
<div class="md4">هر چه دارایی بیشتر احتمال شانس ولیدیت بیشتر و همچنین جریمش هم بیشتر</div>
<div class="md4">در اتریوم ۲ دیگه نمیخواد همه  اطلاعات بلاکچین رو داشته باشی</div>
<div class="md4">اتریوم درجه سختی شبکه رو اینقدر میبره بالا تا کاربرها بیان به سمت اتریوم ۲</div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------DPoS (Delegated Proof of Stake)-->
#### <span class="red">DPoS (Delegated Proof of Stake)</span>
<div class="" align="right" dir="rtl">
<div class="md4">من که مقدار توکنم کمه شانسم کم میشه پس حق رای خودمو میدم به کسی که شانسش بیشتره و اون اگه ماین کرد به منم یه درصدی میده</div>
<div class="md4">66% باید اجماع کنند</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------LPoS (Liquid Proof of Stakee)-->
#### <span class="red">LPoS (Liquid Proof of Stakee)</span>
<div class="" align="right" dir="rtl">
<div class="md4">همان DPos با این تفاوت که نماینده من خودش میتونه حق رای خودشو به یکی دیگه بده</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------Proof of Space-->
#### <span class="red">Proof of Space</span>
<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------Proof of Time-->
#### <span class="red">Proof of Time</span>
<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------POA-->
#### <span class="red">POA</span>
<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------POSA-->
#### <span class="red">POSA</span>
<div class="" align="right" dir="rtl">
<div class="md4">DPOS + POA</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4">Project : BSC</div>
</div>

<!--------------------------------------POC (Proof of Coverage)-->
#### <span class="red">POC (Proof of Coverage)</span>
<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------proof of learning-->
#### <span class="red">proof of learning</span>
<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>

<!--------------------------------------Proof of Authority-->
#### <span class="red">Proof of Authority</span>
<div class="" align="right" dir="rtl">
<div class="md4">Azure BaaS</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>


<!--------------------------------------Cpu + Memory-->
#### <span class="red">Cpu + Memory Hashing</span>
<div class="" align="right" dir="rtl">
<div class="md4">وقتی‌ POW بر اساس محاسبات باشه پس می‌شه دستگاهی درست کرد که فقط همون محاسبات خاص رو انجام بده(ASIC)</div>
<div class="md4">حالا اگر مموری رو هم بیاریم تو بازی، اگر میخوان قدرت محاسباتشون بره بالا حتما باید مموری اضافه کنند و این هزینه بر هست</div>
<div class="md4">مانند Equihash که در کوین ZCash استفاده شده است</div>
<div class="md4">مانند Litecoin که در کوین Scrypt استفاده شده است</div>
</div>

<!--------------------------------------Proof of useful work-->
#### <span class="red">Proof of useful work</span>
<div class="" align="right" dir="rtl">
<div class="md4">setiathome.berkeley.edu</div>
<div class="md4">www.foldingathome.org</div>
<div class="md4">prime search</div>
</div>

<!--------------------------------------Proof of storage-->
#### <span class="red">Proof of storage</span>
<div class="" align="right" dir="rtl">
<div class="md4">Permacoin</div>
<div class="md4">BurstCoin</div>
</div>

<!--------------------------------------non-outsourceable-->
#### <span class="red">non-outsourceable</span>
<div class="" align="right" dir="rtl">
<div class="md4">فقط شخصی‌ بشود ماین کرد</div>
</div>

<!--------------------------------------Proof of stake or virtual mining-->
#### <span class="red">Proof of stake or virtual mining</span>
<div align="right" dir="rtl">
<div class="md4">چرا پول بدیم به دستگاه ماینر سازا و شرکت برق برای ماین کردن کردن </div>
<div class="md4"> خوب هزینه ایی که می‌خوای بکنی‌ رو بده کوین بخر و شانس ماین کردنت رو ببر بالا</div>
<div class="md4">PeerCoin</div>
<div class="md4">Dash</div>
</div>



<!-----------------------------------------------------------Devices----------------------------------------------------------->
<div class="md1"></div>

## Devices

<table><tbody>
<tr><td colspan="2" align="center" bgcolor="D1ECCF">Devices</td></tr>
<tr>
<td  align="center">CPU</td>
<td align="center">20 میلیون در ثانیه</td>
</tr>
<tr>
<td  align="center">GPU</td>
<td align="center">200 میلیون در ثانیه</td>
</tr>
<tr>
<td  align="center">FPGA</td>
<td align="center"><span>دستگاهایی که فقط یک کار را انجام میدهند</span> <span>(1 گیگ در ثانیه)</span></td>
</tr>
<tr>
<td  align="center">ASIC</td>
<td align="center"><span>دستگاهایی که فقط کار مشخص ما را انجام می دهند</span> <span>(120 گیگ در ثانیه)</span></td>
</tr>
</tbody></table>

#### companies

<div class="" align="left" dir="ltr">
<div class="md4">Bitmain | MicroBT</div>
<div class="md4"></div>
<div class="md4"></div>
</div>



<!-----------------------------------------------------------Pool----------------------------------------------------------->
<div class="md1"></div>

##  Pool

<div class="" align="right" dir="rtl">
<div class="md4">یک سری ماینر جمع میشوند و روی یک بلاک کار میکنند، هر کی‌ برنده شد به بقیه هم اندازهٔ قدرت محاسبشون پول میده</div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>



<!-----------------------------------------------------------Note----------------------------------------------------------->
<div class="md1"></div>

## Note

<div class="" align="right" dir="rtl">
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
<div class="md4"></div>
</div>