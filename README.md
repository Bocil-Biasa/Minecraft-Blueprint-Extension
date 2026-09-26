# ⛏️ Minecraft Blueprint Extensions for Pterodactyl

Kumpulan ekstensi/plugin keren untuk panel Pterodactyl menggunakan **Blueprint Framework**. Dilengkapi dengan opsi instalasi manual maupun otomatis menggunakan script CLI bergaya *Composer*.

> **⚠️ PENTING:** Semua proses instalasi **wajib** dijalankan di dalam direktori root Pterodactyl (`/var/www/pterodactyl`) karena Blueprint hanya bekerja di sana.

---

## 🚀 Cara Instalasi

### 1. Auto Installer (Recommended 🌟)
Script ini sudah otomatis berpindah ke direktori Pterodactyl, mengecek Node.js (v22+), memeriksa Blueprint, mengunduh plugin, dan menginstalnya.

Jalankan perintah ini di terminal (dengan akses *sudo/root*):

```bash
bash <(curl -sL https://gist.githubusercontent.com/Bocil-Biasa/b7683d0b9bbc0b33fd5dad218c7e4b07/raw/install-mc-plugins.sh)

```

---

### 2. Manual Installation

Jika ingin menginstal secara manual, pastikan kamu berpindah ke direktori Pterodactyl terlebih dahulu:

1. Masuk ke direktori Pterodactyl:
```bash
cd /var/www/pterodactyl

```


2. Clone repository ekstensi:
```bash
git clone https://github.com/Bocil-Biasa/Minecraft-Blueprint-Extension.git

```


3. Masuk ke folder hasil clone:
```bash
cd Minecraft-Blueprint-Extension

```


4. Install plugin satu per satu menggunakan Blueprint CLI:
```bash
blueprint -install bsp.blueprint
blueprint -install motdm.blueprint
blueprint -install playerlisting.blueprint
blueprint -install vanillatweaks.blueprint
blueprint -install cpuburst.blueprint
blueprint -install srvicimporter.blueprint
bash <(curl -sL https://exeyarikus.info/pterodactyl-region/install)

```



---

## 📦 Daftar Plugin

* [bsp.blueprint](https://builtbybit.com/resources/blue-server-properties-editor-addon.85585/?ref=discover)
* [motdm.blueprint](https://builtbybit.com/resources/minecraft-motd-manager-by-wammuhost.97306/?ref=discover)
* [playerlisting.blueprint](https://builtbybit.com/resources/player-listing.53200/?ref=discover)
* [vanillatweaks.blueprint](https://builtbybit.com/resources/datapack-installer-for-blueprint.81356/?ref=discover)
* [cpuburst.blueprint](https://builtbybit.com/resources/cpu-burst-reduce-lag-spikes-overload.108273/?ref=discover)
* [srvicimport.blueprint](https://builtbybit.com/resources/mc-icon-importer-by-wammuhost.94596/?ref=discover)
* [Region](https://builtbybit.com/resources/pterodactyl-region.73111/?ref=discover)

---

## 🙏 Acknowledgements / TQTO

* **BuiltByBit** ([builtbybit.com](https://builtbybit.com)) - Terima kasih atas sumber daya dan dukungan plugin yang luar biasa.
