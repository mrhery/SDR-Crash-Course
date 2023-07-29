
# Pendidikan Asas Software Defined Radion (SDR)

Sebuah topik pembelajaran asas dalam bidang komunikasi radio dan digital dengan menggunakan SDR.

## 1. Pengenalan
Software Defined Radio (SDR) merujuk kepada komunikasi radio yang mana fungsi-fungsi perkakasan tradisi radion seperti "amplifiers", modulators", "filters" dan lain-lain lagi digantikan degnan sebuah sistem perkomputeran atau perkakasan digital untuk menerima atau memancar. Sistem-sistem ini juga digunapakai untuk membuat analisa spektrum selain dari menerima atau memancarkan data.

Dengan menggunakan SDR, sistem komputer mampu untuk proses dan modulasi/demodulasi/emulasi-kan fungsi-fungsi komunikasi radio degnan lebih fleksibel dan mudah untuk dikonfigurasikan berbanding dengan perkakasan tradisi yang libatkan peralatan yang besar dan banyak.

Teknologi SDR ini digunakan pada banyak tempat dan bidang dalam dunia harini termasuk komunikasi tentera, tempat awam, internet dan pelbagai lagi. Melalui SDR ini, secara kasarnya kita mampu untuk menerima apa-apa data yang dipancarkan melalui gelombang radio termasuklah data dari satelit dan telefon bimbit.

## 2. Amaran
Penggunaan SDR secara umum di khalayak ramai bagi tujuan mencuri dengar panggilan atau SMS atau menceroboh saluran ("channel") komunikasi lain adalah salah disisi undang-undang. Setiap penyampaian di dalam risalah adalah untuk tujuan pendidikan dan kegunaan pada ketika kecemasan seperti bencana, perperangan dan aktiviti-aktiviti yang tidak melanggar undang-undang.

## 3. Perkakasan SDR
Terdapat banyak perkakasan SDR diluar sana dan mempunyai kelebihan dan kekurangan tersendiri. Kami sendiri menggunakan beberapa SDR untuk membuat kajian bagi penulisan risalah ini. Terdapat beberapa ciri-ciri yang perlu diperhatikan dalam memilih SDR mengikut keperluan kita sendiri. Berikut adalah beberapa SDR yang popular dipasaran:

**1. RTL-SDR (Low-Cost RM 100++)**

	Frekuensi: 500khz-1.75Ghz
 
	Mod: Penerima ("receiver")
 
	Bandwidth: 10Mhz
 
	Range: 80dB
	
**2. HackRF (Low-Cost RM 900++)**

	Frekuensi: 1Mhz-6Ghz
 
	Mod: Penerima & Pemancar ("transreceiver") half-duplex
 
	Bandwidth: 20Mhz
 
	Range: ~48dB

**3. LimeSDR (Low-Cost RM 5000++)**

	Frekuensi: 100Khz-3.8Ghz
 
	Mod: Penerima & Pemancar ("transreceiver") full-duplex
 
	Bandwidth: 61.44Mhz+
 
	Range: unknown
		
Terdapat banyak lagi jenis SDR yang lain terutama pengeluaran dari China sendiri. Tetapi antara ciri-ciri yang paling penting adalah frekuensi yang disokong oleh SDR itu sendiri. Kerana penerimaan gelombang radio berbeza-beza mengikut jenis komunikasi. Antara SDR yang lain seperti BladeSDR dan AirSpy yang agak popular. Tetapi perkakasan SDR ini agak sukar untuk didapati dari Malaysia. Tempahan luar negara juga kebanyakkannya adalah daripada China dan sebahagian dari China ini terkadang tidak dapat berfungsi dengan baik. 

Pengalaman kami sendiri telah membeli sebanyak 6 buah SDR dan yang boleh digunakan hanyalah 2 sahaja.

## 4. Kategori-kategori Gelombang Radio
Secara asasnya, frekuensi yang digunakan oleh perkakasan yang berada dimuka bumi adalah tidak sama kategorinya dan frekuensinya yang digunakan dilangit (satelit). Berikut adalah pecahan frekuensi untuk dimuka bumi:

**1. VLF - Very Low Frequency (3Khz - 30Khz)**: Kegunaan navigasi maritim

**2. LF - Low Frequency (30Khz - 300Khz)**: Kegunaan navigasi

**3. MF - Medium Frequency (300Khz - 3Mhz)**: Radio AM Maritim

**4. HF - High Frequency (3Mhz - 30Mhz)**: Radio gelombang pendek, telefon radio

**5. VHF - Very High Frequency (30Mhz - 300Mhz)**: Saluran TV analog, radio FM, navigasi

**6. UHF - Ultra High Frequency (300Mhz - 3Ghz)**: Salurah TV analog/digital, telefon pintar, GPS

**7. SHF - Super High Frequency (3Ghz - 30Ghz)**: Sistem satelit, telekomunikasi gelombang mikro (microwave)

**8. EHF - Extremely High Frequency (30Ghz - 300Ghz)**: Radio astronomi, sistem radar

Dari pecahan diatas, hanya frekuensi bermula 1Ghz-110Ghz sahaja yang digunakan pada satelit (secara rasmi dan umum). Berikut adalah pecahan kategori bagi frekuensi satelit:

![frequency band](https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2013/11/satellite_frequency_bands/13403191-1-eng-GB/Satellite_frequency_bands_article.jpg)

**1. L-Band (1Ghz - 2Ghz)**
L-Band meliputi frekuensi dari kira-kira 1 hingga 2 GHz. Ia digunakan untuk pelbagai aplikasi, termasuk navigasi satelit (GPS), sistem telefon satelit, dan beberapa penyiaran satelit.

**2. S-Band (2Ghz - 4Ghz)**
S-Band meliputi frekuensi dari kira-kira 2 hingga 4 GHz. Ia digunakan untuk komunikasi satelit, sistem radar, dan pemantauan cuaca.

**3. C-Band (4Ghz - 8Ghz)**
C-Band meliputi frekuensi dari kira-kira 4 hingga 8 GHz. Ia biasanya digunakan untuk komunikasi satelit, termasuk penyiaran televisyen dan perkhidmatan internet.

**4. X-Band (8Ghz - 12Ghz)**
X-Band meliputi frekuensi dari kira-kira 8 hingga 12 GHz. Ia digunakan untuk komunikasi satelit tentera dan kerajaan, serta sistem radar.

**5. Ku-Band (12Ghz - 18Ghz)**
Ku-Band meliputi frekuensi dari kira-kira 12 hingga 18 GHz. Ia digunakan secara meluas untuk komunikasi satelit, termasuk penyiaran terus ke rumah (DTH) dan sistem VSAT (Very Small Aperture Terminal).

**6. K-Band (18Ghz - 27Ghz)**
K-Band meliputi frekuensi dari kira-kira 18 hingga 27 GHz. Ia digunakan untuk pelbagai aplikasi, termasuk komunikasi satelit dan sistem radar.

**7. Ka-Band (27Ghz - 40Ghz)**
Ka-Band meliputi frekuensi dari kira-kira 27 hingga 40 GHz. Ia digunakan untuk komunikasi satelit berkapasiti tinggi, termasuk perkhidmatan internet jalur lebar.

**8. Q-Band (33Ghz - 50Ghz)**
Q-Band meliputi frekuensi dari kira-kira 33 hingga 50 GHz. Ia digunakan untuk komunikasi satelit dan pautan gelombang mikro darat.

**9. V-Band (40Ghz - 75Ghz)**
V-Band meliputi frekuensi dari kira-kira 40 hingga 75 GHz. Ia digunakan untuk komunikasi wayarles berkelajuan tinggi dan pautan satelit.

**10. W-Band (75Ghz - 110Ghz)**
The W-Band covers frequencies from approximately 75 to 110 GHz. It is used for high-speed data transmission and radar systems.

Dari senarai diatas, kemungkinan terdapat beberapa "band" yang lain tercicir. Ini kerana kemungkinan ada sesetengah frekuensi digunakan bukan untuk pengetahuan umum. Keperluan SDR akan tertakluk kepada band frekuensi yang ingin diterima/dipancar. Ada beberapa alat yang boleh digunakan untuk menukar ("convert") dari membaca frekuensi yang tinggi kepada pembacaan yang rendah, tetapi konfigurasi begini boleh memberi masalah pada SDR dan data yang diterima mungkin tidak bersih (bercampur baur).

Dalam risalah ini, kami sediakan beberapa contoh untuk membaca data dari beberapa band frekuensi dari yang kurang dari 6Ghz iaitu bermula dari VHF - SHF (sebahagian) atau frekuensi satelit L-Band - C-Band (sebahagian).

 
## 5. Maklumat Satelit
Dianggarkan terdapat lebih 7 ribu satelit yang mengelilingi bumi. Setiap satelit mempunyai kedudukan dan fungsi masing-masing. Kebiasaannya satelit-satelit ini mempunyai maklumat tersendiri daripada website syarikat yang mengendalikan satelit tersebut. Kita boleh dapatkan senarai satelit melalui carian Google "satellite list frequency" untuk dapatkan maklumat.

Maklumat setiap satelit akan disenaraikan dengan format [Nama Satelit] [Posisi] [Band Satelit]. Contoh:

#### Yamal 300K 177.0°W Ku

1. **Yamal 300K** adalah nama bagi satelit itu.
2. **177.0°W** adalah posisi 177.0 darjah dari barat (W = West).
3. **Ku** adalah Ku-Band iaitu frekuensi 12GHz - 18Ghz.

Bagi mendapatkan maklumat fungsi bagi satelit ini boleh dicari dari website syarikat yang mengendalikan Yamal 300K ini. Antara contoh yang lain, sesetengah satelit menggunakan beberapa frekuensi tambahan yang lain seperti contoh:

#### Bangabandhu 1 119.1°East C/Ku

1. **Bangabandhu 1** adalah nama.
2. **119.1°East** adalah posisi 119.1 darjah dari timur (E = East).
3. **C/Ku** adalah C-Band dan Ku-Band iaitu dari 4Ghz - 8Ghz dan 12Ghz - 18Ghz.

Antara lain istilah yang terdapat dalam maklumat satelit adalah seperti LNB (Low Noise Block) seperti contoh:

#### Koreasat 5A 113.1°East LNB KU

1. **Koreasat 5A** adalah nama bagi satelit itu.
2. **113.1°East** adalah posisi 113.1 darjah dari timur (E = East).
3. **LNB** adalah Low Noise Block.
4. **Ku** adalah Ku-Band iaitu frekuensi 12GHz - 18Ghz.

Low Noise Block (LNB) merujuk kepada komponen penerimaan satelit itu sendiri yang biasanya digunakan pada piring satelit untuk menerima pancaran siaran TV dan radio. LNB ini biasanya menerima siaran yang dipantulkan oleh piring dan menukarkan (convert) kepada frekuensi yang lebih rendah untuk diproses. Antara lain fungsi LNB ini adalah untuk "amplification" iaitu membesarkan frekuensi untuk dipancarkan dengan keadaan "low-noise" iaitu kurang gangguan atau campur-baur bagi memastikan pancaran gelombang itu bersih dan kuat.

Dalam risalah ini kita akan mengkaji dan pelajari bagaimana dari SDR kita boleh membaca dan analisis data yang diterima dari beberapa satelit seperti dibawah:

**1. GPS - Global Positioning System (GPS)**
Sebuah satelit yang biasa digunakan untuk mendapatkan posisi/koordinat. Satelit menggunakan frekuensi 1.57542GHz (L-Band)

**2. Inmarsat**
Sebuah syarikat komunikasi satelit global, menggunakan frekuensi L-Band untuk telefon satelit dan perkhidmatan datanya.

**3. Iridium**
Buruj satelit Iridium menggunakan frekuensi L-Band untuk telefon satelit global dan perkhidmatan pemesejannya.


**4. GLONASS - Global Navigation Satellite System**
Satelit GLONASS menggunakan frekuensi L-band sekitar 1.602 GHz untuk perkhidmatan navigasi satelit yang serupa dengan GPS.

Kesemua senarai satelit diatas adalah berfrekuensi L-Band yang mana sesuai dengan perkakasan RTL-SDR (500Khz-1.7Ghz). Bagi perkakasan yang lebih tinggi seperti HackRF (1Mhz - 6Ghz) kita boleh menerima dan analisis data dari satelit berfrekuensi S-Band seperti:

**1. Weather satellites**
Banyak satelit cuaca menggunakan frekuensi S-Band untuk menghantar data cuaca, termasuk imej dan maklumat meteorologi lain.

**2. Radar satellites**
Satelit Radar Apertur Sintetik (SAR) sering menggunakan frekuensi S-Band untuk keupayaan pengimejan dan pengesanan radar mereka.

**3. Scientific satellites**
Sesetengah satelit saintifik menggunakan frekuensi S-Band untuk pelbagai tujuan penderiaan dan penghantaran data.

Bukan sekadar satellit, bahkan mana-mana SDR mampu untuk memintas apa-apa komunikasi radio untuk curi dengar, menghalang dan memancar semula gelombang termasuklah gelombang WiFi, telekomunikasi 3G, 4G dan lain-lain. Biasa RTL-SDR mereka gunakan untuk mencuri dengar komunikasi pesawat udara dan kapal-kapal laut. Meminsta komunikasi adalah menyelahi undang-undang Malaysia. Kami hanya memaparkan cara untuk mendapatkan maklumat yang dibenarkan sahaja.

## Installation (Pemasangan) Software & Operating System (OS)
Dalam risalah ini kita akan belajar menggunakan 2 jenis software (unutk Windows);
1. First party - software yang memang menjadi tunggak API utama bagi HackRF / RTL-SDR
2. Third party - software yang dibangunkan berasaskan API utama diatas.

Diantara kedua-dua software ini, pilihan software third-party adalah lebih mudah untuk digunakan kerana mereka telah bangunkan software itu dalam bentuk yang mudah difahami berbanding API utama itu hanyalah command-line interface (CLI). Akan tetapi, tidak dapat dinafikan, keperluan pengetahun berkenaan API utama itu adalah penting kerana software third-party kadangkala tidak disokong oleh sesetengah device tambahan pula jika kita mahu bangungkan sendiri toolkit untuk SDR HackRF / RTL-SDR kita sendiri.

Bagi muatturun API utama HackRF / RTL-SDR boleh dapati dari repository PhotosSDR: https://downloads.myriadrf.org/builds/PothosSDR/

Bagi software third-party pula kami memilih untuk menggunakan SDR++ dan Wireshark. Kebiasaannya SDR++ adalah cukup untuk menerima/rekod data samaada audio seperti radio FM/AM, L-Band satelit dan lai-lain lagi. Akan tetapi SDR++ bukanlah satu software yang baik untuk membuat analsis paket. Maka bagi analsis paket boleh gunakan Wireshark. Hal ini kerana penerimaan data dari satelit kebanyakkannya adalah data yang telah dienkrip (encrypted data). Maka bagi proses dekripsi (decryption) memerlukan proses analisis terlebih dahulu.

Terdapat sebuah OS yang dibangungkan khas untuk operasi komunikasi radio ini iaitu DragonOS yang mana OS ini adalah Linux. Dalam OS ini semua software untuk komunikasi radio telah terpasang. Muatturun disini: https://cemaxecuter.com/

## Istilah-istilah Konfigurasi
Dalam konfigurasi komunikasi radio ini, terdapat banyak istilah-istilah yang terlibat. Walaubagaimanapun, kami menulis dari sudut umum dan kearah keselamatan siber (CyberSec) bukan terperinci dan khusus untuk komunikasi radio.

**1. Gain Control / LNA (Low-Noise Amplification) Gain**
Kebanyakkan SDR menyokong fungsi LNA ini. Kawalan gain ini boleh dilakukan pada software yang digunakan itu sendiri. Gain ini secara kasarnya adalah tahap sensitiviti untuk menerima gelombang dan semakin tinggi gain mungkin boleh mendapatkan lebih data tetapi "noise" juga akan semakin tinggi. Fungsi LNA ini membantu untuk peningkatan gain dengan kadar "noise" yang lebih rendah. 

Kadangkala gelombang yang agak jauh dari SDR atau antena kita memerlukan gain yang agak tinggi, dan kadangkala kita memerlukan gain yang rendah untuk mendapatkan data yang lebih bersih dan jelas. Gain ini juga dipengaruhi dan mempengaruhi jenis antena yang digunakan.

**2. Automatic Gain Control (AGC)**
Sementara kawalan gain ini memberi kesan kepada gelmbang yang diterima (termasuk noise), maka sesetengah SDR atau software mempunyai ciri-ciri tambahan iaitu AGC yang mampu "auto-tune gain" untuk dapatkan data atau siaran dengan lebih baik dalam keadaan noise yang masuk akal. Tidak semua SDR atau software yang mempunyai ciri-ciri ini. HackRF sendiri tiada ciri-ciri AGC ini (mungkin firmware lebih baru akan ada). 

**3. Sample Rate**
Sample rate ini merujuk kepada jumlah "sample" yang diambil setiap saat daripada frekuensi radio yang kemudiannya ditukar (convert) kepada digital data. Sample rate yang lebih tinggi boleh dikatakan data digital dibaca dengan lebih banyak. Kebiasaanya tetapan ini boleh tetapkan kepada yang paling besar kecuali bagi frekuensi audio seperti FM/AM radio perlu tetapkan ikut keperluan. Hal ini kerana, audio yang didengar secara langsung (live) dengan sample rate yang tinggi mungkin bercampur baur dengan frequency yang tidak penting.

Nilai sample rate ini bergantung kepada jenis SDR yang digunakan. HackRF menyokong sehingga 20Mhz, RTL-SDR hanya 2Mhz sahaja.

**4. Bias-T**
Tetapan bias-T ini membolehkan SDR untuk menajana sedikit elektrik bagi alatan tambahan RF amplifier. Contohnya seperti antena tambahan seperti MLA30+ magnetic loop. Ada setengah SDR mempunyai Bias-T sendiri dan boleh mengesan antenan tambahan itu secara automatik.

**5. Offset Tuning**
Offset tuning ini biasanya digunakan untuk menukarkan band frekuensi yang disokong kapada band yang lain. Tapi penggunaan tetapan ini biasanya bergantung kepada SDR itu sendiri jika tidak menyokong fungsi ini maka memerlukan perkakasan tambahan. Sebagai contoh HackRF yang tidak menyokong frekuensi rendah dari 1Mhz, maka offset tuning boleh membantu untuk menerima data yang kurang dari 1Mhz. 

**6. IQ Correction**
Tetapan ini penting untuk mengimbangi frekuensi bagi perkakasan yang terkesan dengan "DC Spike". Kami sendiri mengalami masalah sebegini pada HackRF kami yang mana pada paparan skrin frekuensi terpada satu "spike" yang mengganggu frekuensi ditengah-tengah graf.

