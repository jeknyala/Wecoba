<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Timeline Dinasti Abbasiyah (750–1258 M)</title>
<style>
:root{--bg:#faf7f0;--card:#fff;--tx:#2a2620;--mu:#6d655a;--bd:#e4dccb;--ac:#0f6b5c;--e1:#0f6b5c;--e2:#b45309;--e3:#6d28d9;--e4:#b91c1c;--pos:#166534;--neg:#991b1b;--posbg:#e7f4ea;--negbg:#fbe9e7;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#17150f;--card:#221f17;--tx:#efe9da;--mu:#a69d8b;--bd:#39342a;--ac:#3fbfa8;--e1:#3fbfa8;--e2:#f5a54a;--e3:#b79bf5;--e4:#f58a8a;--pos:#7fd49a;--neg:#f2a39b;--posbg:#1b2c20;--negbg:#321e1b}}
:root[data-theme="dark"]{--bg:#17150f;--card:#221f17;--tx:#efe9da;--mu:#a69d8b;--bd:#39342a;--ac:#3fbfa8;--e1:#3fbfa8;--e2:#f5a54a;--e3:#b79bf5;--e4:#f58a8a;--pos:#7fd49a;--neg:#f2a39b;--posbg:#1b2c20;--negbg:#321e1b}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font-family:Georgia,"Times New Roman",serif;line-height:1.55}
.wrap{max-width:760px;margin:0 auto;padding:20px 16px 60px}
h1{font-size:1.7rem;margin:.2em 0 .1em}
.sub{color:var(--mu);margin:0 0 14px;font-family:system-ui,sans-serif;font-size:.92rem}
.bar{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);padding:8px 0;z-index:5;font-family:system-ui,sans-serif}
.chips{display:flex;gap:6px;overflow-x:auto;padding-bottom:4px}
.chip{flex:none;border:1px solid var(--bd);background:var(--card);color:var(--tx);border-radius:999px;padding:6px 12px;font-size:.8rem;cursor:pointer}
.chip.on{background:var(--ac);color:var(--bg);border-color:var(--ac)}
.tools{display:flex;gap:8px;margin-top:6px}
.tools input{flex:1;min-width:0;border:1px solid var(--bd);background:var(--card);color:var(--tx);border-radius:8px;padding:7px 10px;font-size:.85rem}
.tools button{border:1px solid var(--bd);background:var(--card);color:var(--tx);border-radius:8px;padding:7px 10px;font-size:.8rem;cursor:pointer}
.tl{position:relative;margin-top:14px;padding-left:26px}
.tl::before{content:"";position:absolute;left:8px;top:0;bottom:0;width:2px;background:var(--bd)}
.item{position:relative;margin-bottom:14px}
.dot{position:absolute;left:-26px;top:16px;width:18px;height:18px;border-radius:50%;background:var(--c);border:3px solid var(--bg)}
.card{background:var(--card);border:1px solid var(--bd);border-left:4px solid var(--c);border-radius:10px;overflow:hidden}
.head{width:100%;text-align:left;background:none;border:0;color:inherit;font:inherit;padding:12px 14px;cursor:pointer;display:block}
.yr{font-family:system-ui,sans-serif;font-weight:700;color:var(--c);font-size:.85rem}
.tt{font-size:1.08rem;font-weight:700;margin:2px 0}
.ld{font-family:system-ui,sans-serif;font-size:.82rem;color:var(--mu)}
.body{display:none;padding:0 14px 14px;font-size:.95rem}
.item.open .body{display:block}
.item.open .arr{transform:rotate(90deg)}
.arr{float:right;color:var(--mu);transition:transform .15s}
.sec{margin-top:10px}
.lb{font-family:system-ui,sans-serif;font-size:.72rem;letter-spacing:.06em;text-transform:uppercase;color:var(--mu);font-weight:700}
.pn{display:grid;gap:8px;margin-top:10px}
.pn div{border-radius:8px;padding:8px 12px}
.pn .p{background:var(--posbg);color:var(--pos)}.pn .n{background:var(--negbg);color:var(--neg)}
.pn ul{margin:4px 0 0;padding-left:18px;color:var(--tx)}
.ev{margin-top:10px;padding:8px 12px;border-radius:8px;border:1px dashed var(--c)}
.e1{--c:var(--e1)}.e2{--c:var(--e2)}.e3{--c:var(--e3)}.e4{--c:var(--e4)}
.empty{color:var(--mu);text-align:center;padding:30px 0;font-family:system-ui,sans-serif}
footer{color:var(--mu);font-size:.78rem;font-family:system-ui,sans-serif;margin-top:20px}
</style>
</head>
<body>
<div class="wrap">
<h1>Timeline Dinasti Abbasiyah</h1>
<p class="sub">750–1258 M · Ketuk kartu untuk membuka detail pemimpin, konflik, kebijakan, hal positif–negatif, dan event besar.</p>
<div class="bar">
<div class="chips" id="chips"></div>
<div class="tools"><input id="q" type="search" placeholder="Cari tokoh atau peristiwa…"><button id="all">Buka semua</button></div>
</div>
<div class="tl" id="tl"></div>
<footer>Tahun dalam Masehi. Periodisasi mengikuti pembagian umum: masa keemasan, dominasi Turki, dominasi Buwaihiyah, dan dominasi Seljuk hingga keruntuhan.</footer>
</div>
<script>
var ERAS=[
{k:"all",n:"Semua"},
{k:"e1",n:"1 · Pembentukan & Keemasan (750–847)"},
{k:"e2",n:"2 · Dominasi Turki (847–945)"},
{k:"e3",n:"3 · Dominasi Buwaihiyah (945–1055)"},
{k:"e4",n:"4 · Seljuk & Keruntuhan (1055–1258)"}];
var D=[
{e:"e1",y:"750",t:"Revolusi Abbasiyah & Berdirinya Dinasti",l:"Abu al-Abbas as-Saffah (750–754)",
 lead:"Abu al-Abbas as-Saffah, pendiri dinasti; didukung Abu Muslim al-Khurasani dari Khurasan.",
 con:"Menumbangkan Bani Umayyah; Pertempuran Zab Besar mengalahkan Marwan II. Keluarga Umayyah diburu, hanya sebagian yang selamat (termasuk Abdurrahman ad-Dakhil).",
 pol:"Pusat pemerintahan dipindah dari Damaskus ke Irak (Kufah, lalu Anbar). Pemerintahan bersifat Islam universal, tidak hanya berpusat pada Arab; mawali (non-Arab) mulai diberi peran.",
 pos:["Persatuan Muslim non-Arab dalam birokrasi","Legitimasi sebagai keluarga Nabi (Bani Hasyim)"],
 neg:["Pembersihan keluarga Umayyah yang brutal","Janji kepada kelompok Alawi (keluarga Ali) tidak terpenuhi, memicu kekecewaan"],
 ev:"Pertempuran Zab Besar (750); as-Saffah dibaiat sebagai khalifah pertama."},
{e:"e1",y:"754–775",t:"Al-Manshur & Pendirian Baghdad",l:"Abu Ja’far al-Manshur",
 lead:"Abu Ja’far al-Manshur, khalifah kedua dan perancang sistem negara Abbasiyah.",
 con:"Menyingkirkan Abu Muslim (755), pemberontakan kelompok Alawi (Muhammad an-Nafs az-Zakiyyah dan Ibrahim), serta oposisi Khawarij.",
 pol:"Membangun Baghdad (Madinat as-Salam, 762) sebagai ibu kota; menata diwan, pos dan intelijen, serta kas negara; mengangkat wazir; mendukung penulisan ilmu dan penerjemahan awal.",
 pos:["Stabilitas dan kas negara kuat","Baghdad menjadi pusat ekonomi dan ilmu"],
 neg:["Otoriter terhadap rival dan oposisi","Pembunuhan Abu Muslim melukai pendukung awal dinasti"],
 ev:"Peletakan batu pertama Baghdad (762)."},
{e:"e1",y:"756–875",t:"Awal Fragmentasi Wilayah",l:"Para gubernur dan dinasti-dinasti otonom",
 lead:"Abdurrahman ad-Dakhil (Umayyah Andalusia), Idris I (Idrisiyah), Ibrahim bin Aghlab (Aghlabiyah), Thahir (Thahiriyah), Ahmad bin Thulun (Thuluniyah).",
 con:"Wilayah jauh dari Baghdad sulit dikendalikan; gubernur membangun kekuasaan turun-temurun.",
 pol:"Khalifah sering mengakui otonomi sebagai ganti pengakuan simbolik dan upeti.",
 pos:["Pusat budaya baru tumbuh (Kordoba, Fes, Kairouan)","Persaingan ilmu dan seni antarwilayah"],
 neg:["Kewibawaan khalifah melemah","Pendapatan pusat menurun"],
 ev:"Umayyah Andalusia berdiri (756); disusul Idrisiyah (788), Aghlabiyah (800), Thahiriyah (821), Thuluniyah (868)."},
{e:"e1",y:"786–809",t:"Harun ar-Rasyid: Puncak Kejayaan",l:"Harun ar-Rasyid",
 lead:"Harun ar-Rasyid, dibantu keluarga Barmakid (Yahya dan Ja’far al-Barmaki) sebagai wazir.",
 con:"Pemberontakan lokal di Afrika Utara dan Khurasan; kemelut sukses takhta; penjatuhan Barmakid (803).",
 pol:"Mendukung ilmu, sastra, dan perpustakaan; membangun rumah sakit dan fasilitas umum; jihad melawan Bizantium; wilayah dibagi untuk dua putranya (al-Amin dan al-Ma’mun) yang kelak memicu perang.",
 pos:["Baghdad menjadi kota terbesar dan terkaya di dunia","Perdagangan, pertanian, dan ilmu berkembang pesat"],
 neg:["Pemborosan istana","Pembagian wilayah untuk putra-putranya menyiapkan perang saudara"],
 ev:"Penumpasan Barmakid (803); hubungan diplomatik dengan Charlemagne."},
{e:"e1",y:"809–813",t:"Perang Saudara al-Amin vs al-Ma’mun",l:"Al-Amin dan al-Ma’mun",
 lead:"Al-Amin (Baghdad, dari ibu Arab) melawan al-Ma’mun (Merv, dari ibu Persia) yang didukung Tahir bin Husain.",
 con:"Al-Amin mencoba mengganti urutan pewaris; al-Ma’mun menolak dan pasukan Khurasan mengepung Baghdad.",
 pol:"Pertarungan sekaligus mencerminkan persaingan elite Arab dan Persia.",
 pos:["Al-Ma’mun menang dan dikenal sebagai pelindung ilmu"],
 neg:["Baghdad rusak parah akibat pengepungan","Perpecahan elite dan menguatnya peran tentara"],
 ev:"Pengepungan Baghdad dan wafatnya al-Amin (813)."},
{e:"e1",y:"813–833",t:"Al-Ma’mun: Baitul Hikmah & Mihnah",l:"Al-Ma’mun",
 lead:"Al-Ma’mun, penguasa dengan minat besar pada filsafat dan sains.",
 con:"Pemberontakan di Mesir dan Persia; pertentangan dengan ulama atas doktrin Mu’tazilah.",
 pol:"Mengembangkan Baitul Hikmah (pusat penerjemahan dan riset); mensponsori astronomi dan matematika; mengadopsi Mu’tazilah sebagai paham resmi dan memulai Mihnah (ujian akidah, 833).",
 pos:["Gerakan penerjemahan Yunani–Suryani–Persia ke Arab","Lahir tokoh seperti al-Khawarizmi dan al-Kindi"],
 neg:["Mihnah memenjarakan dan menekan ulama (Imam Ahmad bin Hanbal)","Ketegangan antara penguasa dan ulama"],
 ev:"Puncak Baitul Hikmah; dimulainya Mihnah (833)."},
{e:"e1",y:"833–842",t:"Al-Mu’tasim & Pindah ke Samarra",l:"Al-Mu’tasim",
 lead:"Al-Mu’tasim, yang merekrut pasukan budak Turki (mamluk).",
 con:"Pemberontakan Babak al-Khurramiyah; perang dengan Bizantium.",
 pol:"Membentuk pasukan Turki sebagai tentara pribadi; memindahkan ibu kota ke Samarra (836) untuk menghindari gesekan dengan warga Baghdad.",
 pos:["Kemenangan di Amorium (838)","Pasukan loyal dan profesional"],
 neg:["Tentara Turki kelak menguasai politik","Samarra memisahkan khalifah dari rakyat"],
 ev:"Penaklukan Amorium (838); Samarra menjadi ibu kota (836)."},
{e:"e2",y:"847–861",t:"Al-Mutawakkil & Anarki Samarra",l:"Al-Mutawakkil",
 lead:"Al-Mutawakkil, penguasa yang menghentikan Mihnah (848).",
 con:"Ketegangan dengan perwira Turki; dibunuh pada 861 atas persetujuan putranya sendiri.",
 pol:"Kembali ke Sunni tradisional, membela ulama hadis; membangun Masjid Agung Samarra dengan menara spiral (Malwiyah).",
 pos:["Berakhirnya Mihnah; Imam Ahmad dihormati","Arsitektur monumental"],
 neg:["Pengeluaran besar","Pembunuhan khalifah membuka era anarki: khalifah dipasang dan dicopot tentara Turki"],
 ev:"Pembunuhan al-Mutawakkil (861) dan Anarki Samarra (861–870)."},
{e:"e2",y:"869–883",t:"Pemberontakan Zanj",l:"Ali bin Muhammad (pemimpin Zanj)",
 lead:"Ali bin Muhammad, pemimpin budak Zanj di rawa Basrah; dihadapi Abu Ahmad al-Muwaffaq (saudara khalifah).",
 con:"Budak pekerja tambang garam dan perkebunan melawan; Basrah dijarah.",
 pol:"Al-Muwaffaq memimpin kampanye bertahun-tahun hingga pemberontakan dipadamkan.",
 pos:["Al-Muwaffaq dan putranya al-Mu’tadid memulihkan wibawa; ibu kota kembali ke Baghdad (892)"],
 neg:["Puluhan ribu korban","Ekonomi Irak selatan rusak"],
 ev:"Penumpasan Zanj (883)."},
{e:"e3",y:"936–945",t:"Amir al-Umara & Masuknya Buwaihiyah",l:"Ar-Radi, al-Mustakfi, dan Ahmad Mu’izz ad-Daulah",
 lead:"Khalifah ar-Radi mengangkat Ibn Ra’iq sebagai Amir al-Umara (936); kemudian Mu’izz ad-Daulah dari Buwaihiyah (Syiah Zaidiyah) menguasai Baghdad (945).",
 con:"Perebutan jabatan Amir al-Umara antara jenderal; pasukan Turki dan Dailam bersaing.",
 pol:"Khalifah tetap sebagai simbol Sunni, sementara Buwaihi mengendalikan militer dan kas.",
 pos:["Seni, sastra, dan ilmu tetap hidup","Khalifah tetap diakui sebagai simbol persatuan"],
 neg:["Kekuasaan riil hilang dari khalifah","Konflik Sunni–Syiah di Baghdad menguat"],
 ev:"Buwaihiyah memasuki Baghdad (945)."},
{e:"e3",y:"945–1055",t:"Dominasi Buwaihiyah",l:"Adhud ad-Daulah dan para khalifah simbolik",
 lead:"Adhud ad-Daulah (puncak Buwaihi) dan khalifah seperti al-Qadir yang menulis dokumen akidah Sunni.",
 con:"Persaingan antar emir Buwaihi; ketegangan kelompok Sunni dan Syiah.",
 pol:"Sistem iqtha’ (tanah sebagai gaji tentara); pembangunan irigasi, rumah sakit (Bimaristan Adhudi); perayaan Syiah seperti Asyura dan Ghadir didukung.",
 pos:["Kemajuan kedokteran dan sains","Sastra dan filsafat berkembang"],
 neg:["Khalifah dibatasi dan bisa dicopot","Ekonomi merosot oleh iqtha’ dan perang antar emir"],
 ev:"Fatimiyah mendirikan Kairo (969) sebagai pesaing Baghdad."},
{e:"e4",y:"1055",t:"Seljuk Masuk Baghdad",l:"Tughril Beg & al-Qa’im",
 lead:"Tughril Beg (Seljuk, Sunni) memasuki Baghdad dan diberi gelar Sultan oleh khalifah al-Qa’im.",
 con:"Seljuk mengusir Buwaihi; konflik dengan Fatimiyah dan Bizantium (Manzikert, 1071).",
 pol:"Pemulihan Sunni; Nizham al-Mulk mendirikan Madrasah Nizhamiyah (1067) di Baghdad dan kota lain.",
 pos:["Sunni dipulihkan dan pendidikan formal tersebar","Stabilitas wilayah"],
 neg:["Sultan memegang kekuasaan nyata, khalifah hanya otoritas religius","Perpecahan internal Seljuk setelah 1092"],
 ev:"Seljuk menguasai Baghdad (1055); Pertempuran Manzikert (1071)."},
{e:"e4",y:"1095–1200an",t:"Perang Salib & Lemahnya Pusat",l:"Para khalifah Baghdad dan sultan Seljuk",
 lead:"Khalifah al-Mustazhir hingga an-Nasir; kemudian dipimpin tokoh seperti Zengi, Nuruddin, dan Shalahuddin di Syam–Mesir.",
 con:"Pasukan Salib merebut Yerusalem (1099); persaingan antar penguasa Muslim.",
 pol:"Khalifah an-Nasir (1180–1225) berusaha menghidupkan kembali kekuasaan Abbasiyah di sekitar Irak.",
 pos:["Kebangkitan Sunni dan jihad; Yerusalem direbut kembali (1187)","Kekhalifahan sedikit pulih secara politik"],
 neg:["Dunia Islam terpecah","Perhatian pada ancaman Mongol minim"],
 ev:"Perang Salib I (1096–1099) dan penaklukan Yerusalem oleh Shalahuddin (1187)."},
{e:"e4",y:"1258",t:"Jatuhnya Baghdad ke Mongol",l:"Al-Musta’shim & Hulagu Khan",
 lead:"Khalifah al-Musta’shim, yang lemah dan dipengaruhi wazir Ibn al-Alqami.",
 con:"Hulagu mengepung Baghdad selama sekitar dua minggu; kota jatuh pada Februari 1258.",
 pol:"Negosiasi gagal; pasukan khilafah dikurangi karena persoalan anggaran.",
 pos:["—"],
 neg:["Pembantaian besar (korban ratusan ribu)","Perpustakaan dan Baitul Hikmah dihancurkan; khalifah dieksekusi"],
 ev:"Runtuhnya Abbasiyah di Baghdad (10 Februari 1258). Sebagian keturunan melanjutkan simbol kekhalifahan di Kairo di bawah Mamluk (sejak 1261) hingga 1517."}
];
var state={era:"all",q:"",all:false};
function esc(s){return String(s).replace(/[&<>]/g,function(c){return{"&":"&amp;","<":"&lt;",">":"&gt;"}[c]})}
function li(a){return"<ul>"+a.map(function(x){return"<li>"+esc(x)+"</li>"}).join("")+"</ul>"}
function render(){
 var tl=document.getElementById("tl"),h="";
 D.forEach(function(d,i){
  if(state.era!=="all"&&d.e!==state.era)return;
  var blob=(d.t+d.l+d.lead+d.con+d.pol+d.ev).toLowerCase();
  if(state.q&&blob.indexOf(state.q)<0)return;
  h+='<div class="item '+d.e+(state.all?" open":"")+'" data-i="'+i+'"><span class="dot"></span><div class="card"><button class="head"><span class="arr">▸</span><div class="yr">'+esc(d.y)+' M</div><div class="tt">'+esc(d.t)+'</div><div class="ld">'+esc(d.l)+'</div></button><div class="body">'
  +'<div class="sec"><div class="lb">Pemimpin</div>'+esc(d.lead)+'</div>'
  +'<div class="sec"><div class="lb">Konflik</div>'+esc(d.con)+'</div>'
  +'<div class="sec"><div class="lb">Kebijakan</div>'+esc(d.pol)+'</div>'
  +'<div class="pn"><div class="p"><div class="lb">Hal positif</div>'+li(d.pos)+'</div><div class="n"><div class="lb">Hal negatif</div>'+li(d.neg)+'</div></div>'
  +'<div class="ev"><div class="lb">Event besar</div>'+esc(d.ev)+'</div></div></div></div>';
 });
 tl.innerHTML=h||'<div class="empty">Tidak ada hasil.</div>';
}
var chips=document.getElementById("chips");
ERAS.forEach(function(e){var b=document.createElement("button");b.className="chip"+(e.k==="all"?" on":"");b.textContent=e.n;b.onclick=function(){state.era=e.k;[].forEach.call(chips.children,function(c){c.classList.remove("on")});b.classList.add("on");render()};chips.appendChild(b)});
document.getElementById("q").oninput=function(e){state.q=e.target.value.trim().toLowerCase();render()};
document.getElementById("all").onclick=function(e){state.all=!state.all;e.target.textContent=state.all?"Tutup semua":"Buka semua";render()};
document.getElementById("tl").onclick=function(e){var hd=e.target.closest(".head");if(hd)hd.closest(".item").classList.toggle("open")};
render();
</script>
</body>
</html>
