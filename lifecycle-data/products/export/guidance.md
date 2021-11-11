---
title: Smernice za izvoz podatkov o življenjskem ciklu
description: Smernice za izvoz informacij o življenjskem ciklu izdelka
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546872"
---
# <a name="lifecycle-data-export-guidance"></a>Smernice za izvoz podatkov o življenjskem ciklu
V tem dokumentu je opisano, kako lahko uporabite datoteko za izvoz izdelka.

## <a name="query-information"></a>Informacije o poizvedbi
V dokumentu Excel so na voljo polja, ki pomagajo prepoznati podatke, izpolnjene v tabeli izdelka.

### <a name="end-of-support"></a>Konec podpore
Po vrednosti konca podpore bodo izdelki filtrirani po datumu konca podpore ali končnih datumih izdaje.

Mogoče vrednosti: Vse (filter ni uporabljen), Leto in Obseg.

### <a name="family"></a>Družina
Vrednost družine filtrira izdelke po nadrejeni ravni v hierarhiji, imenovani družina.

Mogoče vrednosti: Vse (filter ni uporabljen), Ime družine

### <a name="group"></a>Skupina
Vrednost skupine filtrira izdelke znotraj nadrejene ravni (družine) v določeno skupino.

Možne vrednosti: Vse (filter ni uporabljen), Ime skupine

## <a name="table-columns"></a>Stolpci tabele
V tabeli izdelkov so stolpci, ki določajo izdelke, različice, izdaje in ustrezne datume podpore.

> [!NOTE]
> Na voljo bo vrstica za vsako kombinacijo izdelkov, različic in izdaj.

### <a name="product"></a>Izdelek
Ime izdelka.

### <a name="edition"></a>Izdaja
Stolpec »različica« bo izpolnjen, ko izdelek vsebuje različice. Če ni različice izdelka, bo to polje prazno.

### <a name="release"></a>Izdaja
Stolpec »Izdaja« bo izpolnjen, ko izdelek vsebuje več izdaj.
Če ima izdelek le eno izdajo, bo to polje prazno.

### <a name="support-policy"></a>Pravilnik podpore
V tem polju je določen pravilnik podpore, ki velja za izdelek.

Možne vrednosti: [Nespremenljivo,](/lifecycle/policies/fixed) [Sodobno](/lifecycle/policies/modern), Komponenta

### <a name="start-date"></a>Datum začetka
Datum začetka podpore za izdelek.

### <a name="mainstream-date"></a>Osnovni datum
Ko je pravilnik podpore **nespremenljiv** **ali komponenta**, je to datum osnovnega končnega datuma izdelka.
  
Če je pravilnik podpore **sodoben**, bo to prazno.

### <a name="extended-end-date"></a>Končni datum razširjene podpore
Ko je pravilnik podpore **nespremenljiv** ali **komponenta**, je to končni datum razširjene podpore izdelka.

Če je pravilnik podpore **sodoben**, bo to prazno.

### <a name="retirement-date"></a>Datum upokojitve
Ko je pravilnik podpore **nespremenljiv** ali **komponenta,** bo to prazno.

Če je pravilnik podpore **sodoben**, bo to datum upokojitve izdelka.

### <a name="release-start-date"></a>Datum začetka izdaje
Datum začetka podpore za izdajo. Če ima izdelek le eno izdajo, bo to polje prazno.
 
### <a name="release-end-date"></a>Končni datum izdaje
Datum konca podpore za izdajo.
Če ima izdelek le eno izdajo, bo to polje prazno.

### <a name="docs-url"></a>URL dokumenta
URL do razširjene dokumentacije.
