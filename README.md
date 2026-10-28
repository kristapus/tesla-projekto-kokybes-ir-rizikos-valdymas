# Tesla įvaizdžio gerinimo projektas

KTU modulis **S190M182 „Projektų rizikos ir kokybės valdymas“**. Grupė: **Kristupas Kuras, Lukas Račkauskas ir Žygimantas Latkauskas**.

Tęsiame ankstesnių semestrų projektą ir rengiame jo kokybės bei rizikos valdymo planą. Pagal naujesnės ataskaitos uždavinius darbinė apimtis yra tvarumo komunikacija Baltijos šalyse, 2 teminiai renginiai, 2 CSR akcijos ir 3 trumpi vaizdo įrašai per aktyvų mėnesį. Šią siauresnę bazę grupė dar turi peržiūrėti.

**Būsena 2026-10-28:** kokybės dalis parengta pagal užduoties šablono 1–5 skyrius: išlaikyti 10 kriterijų, papildytos fazių ir procesų lentelės, renginio, CSR ir poveikio vertinimo procedūros, kontrolės protokolas bei patikrų sąnaudų modelis. Pagrindinis dokumentas yra v0.4, jo PDF kopija – 23 puslapių. Esama 8 skaidrių kokybės santrauka išlieka suderinta. Rizikų dalis šia užduotimi nerengta pagal žmogaus nurodymą. Rodiklių ribos, vardiniai vaidmenys, kampanijos trukmė ir biudžeto neatitikimai dar nesuderinti. Faktinių kampanijos ar CSR rezultatų matavimų nepateikta; pavyzdiniai skaičiavimai nėra atliktų veiklų įrodymai.

## Bendra saugykla

[GitHub projekto repozitorija](https://github.com/kristapus/tesla-projekto-kokybes-ir-rizikos-valdymas). Pagrindinė šaka – `main`.

Kolegoms pasiimti visą projektą:

```sh
git clone https://github.com/kristapus/tesla-projekto-kokybes-ir-rizikos-valdymas.git
```

Prieš darbą patikrinkite naujausius bendrus pakeitimus. Vienu metu pagrindinį DOCX redaguoja vienas sutartas žmogus arba agentas. Baigę atnaujinkite kopijas, pakeitimų žurnalą ir įkelkite savo commit į remote pagal `AGENTS.md` taisykles.

## Nuo ko pradėti

1. Pasiimkite visą **`Tesla-projekto-kokybes-ir-rizikos-valdymas`** aplanką: klonuokite saugyklą arba išskleiskite perduotą paketą. Išlaikykite vidinę struktūrą. Šaltinių ir universiteto šablono kopijos yra viduje; ankstesnio autoriaus kompiuterio nereikia.
2. DI agentui nurodykite perskaityti **[AGENTS.md](AGENTS.md)** ir naujausius **[PAKEITIMU_ZURNALAS.md](PAKEITIMU_ZURNALAS.md)** įrašus. Ne visos programos `AGENTS.md` perskaito automatiškai.
3. Atverkite [pagrindinį Word dokumentą](05_Tesla_kokybes_dalis/Tesla_kokybes_ir_rizikos_valdymo_planas.docx). Prieš keisdami bendrą failą susitarkite, kuris kolega ar agentas jį redaguoja.

Pagrindinį dokumentą rengti **DOCX formatu pagal universiteto rašto darbo šabloną**, išlaikant KTU titulinį, paraštes, stilius ir automatinį turinį. Plano PDF ir MD yra išvestinės kopijos; jas atnaujinti pakeitus DOCX. Pilnos agentų darbo, šaltinių tikrinimo, archyvavimo, laikinų failų ir Git commit / push taisyklės yra `AGENTS.md`.

## Failai ir aplankai

Visi keliai yra santykiniai nuo šio projekto aplanko.

| Failas / aplankas | Paskirtis |
|---|---|
| `AGENTS.md` | Projekto santrauka, dabartinė būsena, failų rodyklė ir taisyklės DI agentams |
| `PAKEITIMU_ZURNALAS.md` | Kas pakeista, kodėl, kas patikrinta ir kokie sprendimai liko atviri |
| `01_Oficiali_medziaga` | Moodle medžiaga; `Rasto_darbo_sablonas.docx` nustato formatą, o `Projekto_kokybes_ir_rizikos_planas_uzduotis_2026.docx` – plano turinio struktūrą |
| `02_Projekto_ruosinys` | Ankstesni ruošiniai ir analizė; svarbus `Saltiniu_faktai_ir_neatitikimai.md` registras. Senais ruošiniais neperrašyti aktualaus DOCX |
| `03_Reikalavimai_ir_saltiniai` | Grupinio darbo reikalavimai, kalendorius ir medžiagos kilmė |
| `04_Ankstesniu_semestru_dokumentai` | Nepakeistos A1 projekto ataskaitos, A2 planavimo darbo ir A3 rinkos analizės kopijos |
| `05_Tesla_kokybes_dalis` | Aktualus planas, jo kopijos ir pristatymas. Plano failų bazė `Tesla_kokybes_ir_rizikos_valdymo_planas` su `.docx`, `.pdf`, `.md`; pristatymas turi priesagą `_pristatymas` ir `.pptx` / `.md` |
| `06_Archyvas` | Ankstesnės tikrų dokumentų ir instrukcijų versijos; tai istorija, ne aktualaus plano šaltinis |

## Spalio 29 dienos pristatymas

**2026-10-29, ketvirtadienį, numatytas neformalus kokybės dalies pažangos aptarimas.** Remiamės ankstesniame modulyje parengtu konkrečiu projektu; užduotis savaime nereikalauja sukurti naujos programos. Kalendoriuje tą dieną taip pat numatyta 6 tema apie kokybės valdymo metodus ir problemų sprendimą. Tikslus paskaitos pradžios laikas peržiūrėtuose dokumentuose nenurodytas.

Pasirengti parodyti:

- projekto tikslą, apimtį, rezultatus ir suinteresuotas šalis;
- kokybės reikalavimus bei rodiklius su ribomis, matavimu, dažniu, atsakingu asmeniu, įrodymu ir reakcija neatitikus;
- ryšį su projekto fazėmis ir veiklomis, atsakomybes, prevencines peržiūras, kontrolę ir tobulinimą;
- vieną konkrečią grandinę nuo reikalavimo iki priėmimo ar taisymo; neatliktą matavimą žymėti hipotetiniu;
- parengtos dalies būseną ir klausimus grupės bei dėstytojos aptarimui.

Tai pasirengimo rekomendacija pagal šabloną ir vertinimo kriterijus. Oficialiai nepaskelbta šio tarpinio pristatymo trukmė, privalomas skaidrių skaičius, atskiras įkėlimo terminas ar minimalus užbaigtumo procentas. **8 skaidrės yra mūsų pasirinkta struktūra.**

## Terminai ir vertinimas

| Data | Veiksmas |
|---|---|
| 2026-10-29 | Kokybės dalies progreso pristatymas |
| 2026-11-26 | Rizikų dalies progreso pristatymas |
| 2026-12-13 23:59 | Galutinio kokybės ir rizikos valdymo plano įkėlimas į Moodle |
| 2026-12-17 | Galutinio plano konsultacija; kalendoriuje ir pakartotiniai atsiskaitymai |
| Sausio egzaminas | Individualus grupės plano gynimas; tiksli data nepatvirtinta |

Informacija tikrinta 2026-10-22; prieš atsiskaitymą patikrinti oficialius pakeitimus. Nesudalyvavus tarpiniuose pristatymuose, pagal užduoties aprašą netenkama galimybės aptarti galutinį planą prieš sausio gynimą.

Modulio pažymys: projekto ataskaita 40 %, diskusija 20 %, du tarpiniai egzaminai kartu 40 %. **Pačios ataskaitos** kriterijai – kokybės planavimas, užtikrinimas / kontrolė / tobulinimas, rizikos, nuoseklumas ir individualus gynimas – po 20 %. Tai skirtingi vertinimo lygmenys. Visi nariai turi gebėti pagrįsti visą planą.

## Tekstas naujam DI agentui

> Dirbk su šiame aplanke esančiu „Tesla įvaizdžio gerinimo“ projektu. Pirmiausia perskaityk AGENTS.md ir PAKEITIMU_ZURNALAS.md, tada aktualų DOCX bei užduočiai reikalingus oficialius reikalavimus ir šaltinius. Laikykis AGENTS.md taisyklių. Tęsk esamą darbą universiteto Word šablone. Atskirai žymėk faktus, patvirtintus sprendimus, siūlomas prielaidas ir hipotetinius pavyzdžius. Prieš perrašydamas failą patikrink kolegų pakeitimus. Baigęs atnaujink susijusias kopijas bei pakeitimų žurnalą ir atlik AGENTS.md nustatytus Git veiksmus, jei Git ir remote sukonfigūruoti. Mano dabartinė užduotis: [įrašyk konkretų darbą].

## Šaltiniai ir medžiagos ribos

[Grupinio darbo aprašas](https://moodle.ktu.edu/mod/page/view.php?id=512626), [studijų kalendorius](https://moodle.ktu.edu/mod/page/view.php?id=624187), [galutinio pateikimo užduotis ir šablonas](https://moodle.ktu.edu/mod/assign/view.php?id=526702). Gali reikėti KTU prisijungimo.

Surinktos įvadinės ir 1, 2, 4 temų skaidrės. Atskirų 3, 5, 6 temų failų surinkimo metu nebuvo matyti; papildomų interneto pavyzdžių nuorodos yra šaltinių sąraše. Šablono istorinės 2017 m. datos ir pavyzdiniai vardai nėra šio projekto faktai. Moodle pateikto ISO failo buvimas nepatvirtina, kad tai naujausia ar visa standarto redakcija.

Galutinę pateikiamą versiją peržiūri grupė. Parengti DI dokumentai savaime nepatvirtina nei veiklų atlikimo, nei dėstytojo pritarimo planui.
