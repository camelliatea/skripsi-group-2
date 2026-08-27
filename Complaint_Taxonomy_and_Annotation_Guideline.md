# KAI Commuter Line Complaint Taxonomy and Annotation Guideline

---

## A. Purpose and General Rules
This annotation guideline was developed as a reference for all annotators in labeling Commuter Line user complaint posts on Platform X, with the aim of ensuring consistency and objectivity in inter-annotator labeling. All annotators must follow the following two rules.

1. **Single-label Classification**: each post may be assigned only one label from the five available categories: **Delay, Overcrowding, Cleanliness, Safety, and Service**.
2. The label is determined based on the final physical or emotional aspect directly experienced by the user, rather than on the root cause of the complained condition.

## B. Category Definitions and Keywords
The dataset is classified into five main categories: **Delay, Overcrowding, Safety, Cleanliness, and Service**. If a post contains multiple complaints, the labeling decision must follow the following priority hierarchy:

**Safety > Overcrowding > Cleanliness > Delay > Service**

where the **>** symbol indicates a higher priority level.

For example, a post complaining about a train delay that causes passenger accumulation on the platform must be labeled as **Overcrowding**. This is because overcrowding is the final physical impact directly experienced by the passenger and has a higher position in the priority hierarchy than **Delay**.

The definitions and keywords for each complaint category are described below.

| Category | Description |
|---|---|
| **Delay** | The train is late, held up, affected by an operational disruption, operates on an inconsistent schedule, or does not arrive according to schedule. **Keywords:** telat, terlambat, delay, ngaret, molor, tertahan, pending, antre, lambat, gangguan, stuck, berhenti, mogok, nungguin |
| **Overcrowding** | Crowded, congested, or tightly packed conditions inside trains or in station areas, including platforms, escalators, and entrances. **Keywords:** padat, sesak, penuh, numpuk, crowded, berdesakan, membludak, overload, desak |
| **Cleanliness** | Dirty, unpleasant-smelling, or unhygienic conditions inside trains or in station environments. This does not include odors or conditions indicating physical danger. **Keywords:** kotor, bau, jorok, kumuh, dekil, becek, pesing, sampah, lembap, kecoak, debu |
| **Safety** | Threats to passengers' physical safety, criminal acts, technical or physical hazards that may cause injury, or behavior that threatens safety. **Keywords:** bahaya, jatuh, kegencet, copet, pelecehan, asap, panik, darurat, rawan, rusak, pelaku, maling, kejepit, pingsan |
| **Service** | The attitude, responsiveness, or performance of field staff, including complaints regarding digital services and policies implemented by the service provider. **Keywords:** petugas, pelayanan, responsif, cuek, error, informasi, bantuan, komplain, tidak responsif, tidak ramah, tidak membantu, aplikasi |
| **Exclusion** | Questions that do not describe a negative experience that has already occurred, or general expressions of frustration that do not specify a particular complaint. |

## C. Conflict Resolution Rules
If a post contains more than one complaint aspect, the annotator must determine the label based on the aspect most directly experienced by the user, as shown in the following resolution table.

| Root Cause | Final Experienced Aspect | Label | Rationale |
|---|---|---|---|
| Train delay | Passengers become crowded and accumulate | **Overcrowding** | The physical impact directly experienced by the user is the increased passenger density in the station area or inside the train. |
| Air conditioning is not functioning | Passengers feel stuffy and have difficulty breathing | **Overcrowding** | The effects, such as a feeling of congestion, stuffiness, and reduced spatial comfort inside the train, are directly experienced by the user. |
| Staff are not responsive | Pickpocketing occurs or a passenger falls | **Safety** | The complaint is directly related to threats to safety and security during the journey. |
| Severe crowding | A passenger is stepped on or trapped | **Safety** | The condition poses a risk of physical injury that directly affects user safety. |
| Information in the application is delayed | The user misses the train | **Delay** | The issue directly disrupts the user's travel plan because of schedule inconsistency. |
| Cleaning staff are absent | The toilet is dirty and smells of urine | **Cleanliness** | The user directly experiences an unclean environment that is uncomfortable to use. |
| Burning smell after the train brakes | The train stops for a long time | **Safety** | Although the user experiences a longer waiting time, the complaint directly indicates a condition that may endanger the user's life. |

---

## A. Tujuan dan Aturan Umum
Panduan anotasi ini disusun sebagai acuan bagi seluruh anotator dalam proses pelabelan data cuitan keluhan pengguna Commuter Line pada platform X untuk memastikan konsistensi dan objektivitas hasil pelabelan antaranotator. Seluruh anotator wajib mengikuti dua ketentuan berikut.

1. **Single-label Classification**, yaitu setiap cuitan hanya boleh dilabeli dengan satu kategori dari lima kategori yang tersedia: **Keterlambatan, Kepadatan, Kebersihan, Keamanan, dan Pelayanan**.
2. Label ditentukan berdasarkan aspek fisik atau emosional terakhir yang secara langsung dirasakan oleh pengguna, bukan berdasarkan akar penyebab terjadinya kondisi yang dikeluhkan.

## B. Definisi dan Kata Kunci Kategori
Dataset diklasifikasikan ke dalam lima kategori utama, yaitu **Keterlambatan, Kepadatan, Keamanan, Kebersihan, dan Pelayanan**. Apabila sebuah cuitan mengandung beberapa keluhan sekaligus, keputusan label wajib mengacu pada urutan hierarki prioritas sebagai berikut:

**Keamanan > Kepadatan > Kebersihan > Keterlambatan > Pelayanan**

dengan simbol **>** menunjukkan tingkat prioritas yang lebih tinggi.

Sebagai contoh, sebuah cuitan yang mengeluhkan keterlambatan kereta sehingga menyebabkan penumpukan penumpang di peron wajib dilabeli sebagai **Kepadatan**. Hal ini karena kondisi padat merupakan dampak fisik terakhir yang dirasakan oleh penumpang dan memiliki posisi hierarki yang lebih tinggi dibandingkan **Keterlambatan**.

Adapun definisi serta kata kunci bagi masing-masing kategori keluhan dijelaskan sebagai berikut.

| Kategori | Deskripsi |
|---|---|
| **Keterlambatan** | Kereta terlambat, tertahan, terjadi gangguan operasional, jadwal tidak sesuai, atau kereta tidak muncul sesuai jadwal. **Kata Kunci:** telat, terlambat, delay, ngaret, molor, tertahan, pending, antre, lambat, gangguan, stuck, berhenti, mogok, nungguin |
| **Kepadatan** | Kondisi penuh sesak atau berdesakan di dalam kereta maupun di area stasiun, termasuk peron, eskalator, dan pintu masuk. **Kata Kunci:** padat, sesak, penuh, numpuk, crowded, berdesakan, membludak, overload, desak |
| **Kebersihan** | Kondisi kotor, bau, atau tidak higienis di kereta maupun lingkungan stasiun. Tidak termasuk bau atau kondisi yang mengindikasikan bahaya fisik. **Kata Kunci:** kotor, bau, jorok, kumuh, dekil, becek, pesing, sampah, asap, lembap, kecoak, debu |
| **Keamanan** | Ancaman terhadap keselamatan fisik penumpang, tindak kriminal, bahaya teknis atau fisik yang berpotensi menimbulkan cedera, atau perilaku yang mengancam keselamatan. **Kata Kunci:** bahaya, jatuh, kegencet, copet, pelecehan, asap, panik, darurat, rawan, rusak, pelaku, maling, kejepit, pingsan |
| **Pelayanan** | Sikap, respons, atau kinerja petugas di lapangan, termasuk keluhan terhadap layanan digital serta kebijakan yang diterapkan oleh penyedia layanan. **Kata Kunci:** petugas, pelayanan, responsif, cuek, error, informasi, bantuan, komplain, tidak responsif, tidak ramah, tidak membantu, aplikasi |

## C. Aturan Resolusi Konflik
Apabila sebuah cuitan mengandung lebih dari satu aspek keluhan, anotator wajib menentukan label berdasarkan aspek yang paling langsung dirasakan oleh pengguna, sebagaimana yang disajikan pada tabel resolusi berikut.

| Akar Masalah | Aspek Akhir yang Dirasakan | Label | Alasan |
|---|---|---|---|
| Kereta terlambat | Penumpang sesak dan menumpuk | **Kepadatan** | Karena dampak fisik yang secara langsung dirasakan oleh pengguna adalah meningkatnya kepadatan penumpang di area stasiun maupun kereta. |
| AC mati | Penumpang pengap dan sulit bernapas | **Kepadatan** | Karena dampaknya, seperti rasa sesak, pengap, dan berkurangnya kenyamanan ruang di dalam kereta, dirasakan secara langsung oleh pengguna. |
| Petugas tidak sigap | Terjadi copet atau penumpang terjatuh | **Keamanan** | Karena secara langsung berkaitan dengan ancaman keselamatan dan keamanan selama perjalanan. |
| Desak-desakan | Penumpang terinjak atau terjepit | **Keamanan** | Karena berisiko cedera fisik yang secara langsung memengaruhi keselamatan pengguna. |
| Informasi di aplikasi terlambat | Pengguna tertinggal kereta | **Keterlambatan** | Karena secara langsung mengganggu rencana perjalanan pengguna akibat ketidaksesuaian jadwal. |
| Petugas kebersihan tidak hadir | Toilet kotor dan berbau pesing | **Kebersihan** | Karena pengguna secara langsung merasakan kondisi lingkungan yang tidak bersih dan tidak nyaman digunakan. |
| Bau gosong setelah kereta mengerem | Kereta berhenti lama | **Keamanan** | Meskipun mengalami waktu tunggu yang lebih lama, keluhan ini secara langsung berpotensi membahayakan nyawa pengguna. |
| **Eksklusi** | Hanya pertanyaan tanpa keluhan pengalaman negatif yang sudah terjadi, atau ungkapan frustasi umum tanpa merinci pada keluhan spesifik. |
