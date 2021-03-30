# SolidWorks PCB / Altium biblioteka
KTU Elektros ir elektronikos fakulteto studentų sukurtu komponentų biblioteka.
 
[Templates](https://github.com/Aleksandrovas/KTU_Lib/tree/main/Templates) - schemų, komponentų sąrašo (BOM) šablonai

[SchLib](https://github.com/Aleksandrovas/KTU_Lib/tree/main/SchLib) - komponentų simboliai (schematic symbols)

[PcbLib](https://github.com/Aleksandrovas/KTU_Lib/tree/main/PcbLib) - komponentų topologiniai brėžiniai (footprints)


# Komponentų įvedimo taisyklės
Visi komponentai esantys bibliotekoje privalo turėti šiuos sutartinius parametrus:<br/>
• Manufacturer – gamintojas<br/>
• Manufacturer Part Number – gamintojo kodas<br/>
• Part Type – komponento tipas savo klasėje<br/>
• Value – komponento pavadinimas arba nominalas<br/>
• Mounting – montavimo technologija: SMD arba THD <br/>
• Package – komponento korpuso tipas<br/>
• Supplier 1 – tiekėjas: Farnell, TME, Digi-Key, Mouser;<br/>
• Supplier Part Number 1 – tiekėjo užsakymo kodas<br/>
• ComponentLink1Description - Datasheet (šio užrašo nereikia keisti)<br/>
• ComponentLink1URL - nuoroda į .pdf techninę dokumentaciją<br/>


Priklausomai nuo komponento kategorijos įvedami papildomi parametrai.<br/>

**Rezistoriai**<br/>
• Part Type - rezistoriaus tipas, pvz. Thick Film, Thin Film arba Metal Film<br/> 
• Value - rezistoriaus varža<br/>
• Voltage - rezistoriaus įtampa<br/>
• Power - rezistoriaus galia<br/>
• Tolerance - rezistoriaus tikslumas<br/>
• Temperature Coefficient - temperatūrinis koeficientas<br/>

Skiltyje Symbol Reference įvedamas tikslus gamintojo kodas.<br/>
Skiltyje Description - įvedamas trumpas rezistoriaus aprašas, pavyzdžiui:<br/>
RES 100K, ±10%, 125mW, 150V, 0603 [1608 Metric], Thick Film<br/>

**Kondensatoriai**<br/>
• Part Type - kondensatoriaus tipas, pvz. MLCC, Tantalum arba Electrolytic<br/> 
• Value - kondensatoriaus talpa<br/>
• Voltage - kondensatoriaus įtampa<br/>
• Dielectric - kondensatoriaus dielektrikas: C0G, NP0, X7R, Y5V, Z5U<br/>
• Tolerance - kondensatoriaus tikslumas<br/>

Skiltyje Symbol Reference įvedamas tikslus gamintojo kodas.<br/>
Skiltyje Description - įvedamas trumpas kondensatoriaus aprašas, pavyzdžiui:<br/>
CAP MLCC, 100nF, 25V, 0603 [1608 Metric], ±10%, X7R<br/>

**Indukčiai**<br/>
• Part Type - tipas<br/> 
• Value - ritės induktyvumas<br/>
• Current - ritės srovė<br/>
• Voltage - ritės įtampa<br/>
• Tolerance - ritės tikslumas<br/>

Skiltyje Symbol Reference įvedamas tikslus gamintojo kodas.<br/>
Skiltyje Description - įvedamas trumpas indukčio aprašas, pavyzdžiui:<br/>
IND 1nH, 1A, 50V, 0603 [1608 Metric], ±10%<br/>
