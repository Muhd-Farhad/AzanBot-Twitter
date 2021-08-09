<!-- PROJECT LOGO -->
<br />
<p align="center">
    <a href="https://github.com/HachiroSan/AzanBot-Twitter">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">AzanBot-Twitter</h3>

  <p align="center">
    AzanBot is a Malaysia Islamic prayer alert bot for Twitter. It's a simple script based on Python 3.9.
    <br />
    <br />
    <a href="#Installation">Installation</a>
    ·
    <a href="#Usage">Usage</a>
    ·
    <a href="#Operating-System">Operating System</a>
  </p>
</p>


## Installation

Please install the required package from requirements.txt before proceeding.

```bash
pip install -r requirements.txt
```

## Usage
1. Update your Twitter APIs in config.ini 
2. Specify the prayer zone, refer to zone code below
3. Run app.py
```python
# JOHOR
JHR01 - PULAU AUR DAN PULAU PEMANGGIL
JHR02 - JOHOR BAHRU, KOTA TINGGI, MERSING
JHR03 - KLUANG, PONTIAN
JHR04 - BATU PAHAT, MUAR, SEGAMAT, GEMAS JOHOR

# KEDAH
KDH01 - KOTA SETAR, KUBANG PASU, POKOK SENA (DAERAH KECIL)
KDH02 - KUALA MUDA, YAN, PENDANG
KDH03 - PADANG TERAP, SIK
KDH04 - BALING
KDH05 - BANDAR BAHARU, KULIM
KDH06 - LANGKAWI
KDH07 - PUNCAK GUNUNG JERAI

# KELANTAN
KTN01 - BACHOK, KOTA BHARU, MACHANG, PASIR MAS, PASIR PUTEH, TANAH MERAH, TUMPAT, KUALA KRAI, MUKIM CHIKU
KTN03 - GUA MUSANG (DAERAH GALAS DAN BERTAM), JELI, JAJAHAN KECIL LOJING

# MELAKA
MLK01 - SELURUH NEGERI MELAKA

# NEGERI SEMBILAN
NGS01 - TAMPIN, JEMPOL
NGS02 - JELEBU, KUALA PILAH, PORT DICKSON, REMBAU, SEREMBAN

# PAHANG
PHG01 - PULAU TIOMAN
PHG02 - ROMPIN, PEKAN, MUADZAM SHAH DAN KUANTAN
PHG03 - MARAN, CHENOR, TEMERLOH, BERA, JENGKA DAN JERANTUT
PHG04 - BENTONG, RAUB DAN LIPIS
PHG05 - BUKIT TINGGI, GENTING SEMPAH, DAN JANDA BAIK
PHG06 - CAMERON HIGHLANDS, BUKIT FRASER GENTINGDAN GENTING HIGHLANDS

# SELANGOR
SGR01 - GOMBAK, PETALING, SEPANG, HULU LANGAT, HULU SELANGOR, S.ALAM
SGR02 - KUALA SELANGOR, SABAK BERNAM
SGR03 - KLANG, KUALA LANGAT

# TERENGGANU
TRG01 - KUALA TERENGGANU, MARANG, KUALA NERUS
TRG02 - BESUT, SETIU
TRG03 - HULU TERENGGANU
TRG04 - DUNGUN, KEMAMAN

# SARAWAK
SWK01 - LIMBANG, LAWAS, SUNDAR, TRUSAN
SWK02 - MIRI, NIAH, BEKENU, SIBUTI, MARUDI
SWK03 - PANDAN, BELAGA, SUAI, TATAU, SEBAUH, BINTULU
SWK04 - SIBU, MUKAH, DALAT, SONG, IGAN, OYA, BALINGIAN, KANOWIT, KAPIT
SWK05 - SARIKEI, MATU, JULAU, RAJANG, DARO, BINTANGOR, BELAWAI
SWK06 - LUBOK ANTU, SRI AMAN, ROBAN, DEBAK, KABONG, LINGGA, ENGKELILI, BETONG, SPAOH, PUSA, SARATOK
SWK07 - SERIAN, SIMUNJAN, SAMARAHAN, SEBUYAU, MELUDAM
SWK08 - KUCHING, BAU, LUNDU, SEMATAN
SWK09 - ZON KHAS (KAMPUNG PATARIKAN)

# WILAYAH PERSEKUTUAN
WLY01 - KUALA LUMPUR, PUTRAJAYA
WLY02 - LABUAN
```
## Operating System
Application works for both Linux and Windows. (Tested on Ubuntu 20.04 and Windows 10 21H1)

For Linux, if you want to host multiple bots, use tmux or screen for better management. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
