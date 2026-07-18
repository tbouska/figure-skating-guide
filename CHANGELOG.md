# Changelog

Všechny podstatné změny v tomto projektu jsou zaznamenány v tomto souboru.

## [Unreleased]

### Changed

- **guide**: nohy značené vztahově dvěma barvami (magenta a petrolejová,
  stejná barva = stejná noha) místo absolutního L/P – tečky odrazu a dopadu
  i hvězdička špičky na stopě mají stejné barvy jako nohy panáčka, takže
  „dopad na píchající" a „stejná noha" jsou vidět jako shoda barev bez
  ohledu na směr točení
- **guide**: bohatší animace – oddělený vodorovný (lineární) a svislý
  (zrychlovaný) pohyb dává parabolický oblouk skoku, rotace ve vzduchu
  stroboskopickým převracením s oběma viditelnýma nohama, přikrčení,
  dosednutí s prohnutím, stín pod bruslařem, obláček při dopadu; na stopě
  shora jede kapkovitý bruslař s natočením (u axelu viditelně končí zády)
  a stopa se kreslí průběžně pod ním

- **guide**: přepracované vizualizace skoků na dvojí pohled – stopa na ledě
  shora (tvar nájezdu, barvy hran, píchnutí špičkou, nohy L/P, počet otáček)
  plus zjednodušený boční profil s vystřídanými pózami místo 3D otáčení
- **guide**: zpřesněný obsah – flip vs. lutz vysvětlen přes vnitřní/vnější
  hranu (protioblouk), salchow vs. rittberger přes švih volné nohy vs.
  zkřížené nohy, doplněna 1½ otáčky u axelu, opraveno tvrzení „jediný skok
  na stejné noze" na „jediný hranový skok", přidána legenda a poznámka o
  směru točení a shodném dopadu všech skoků

### Fixed

- **guide**: nedefinovaná CSS proměnná `--text-main` v porovnávacím dialogu
