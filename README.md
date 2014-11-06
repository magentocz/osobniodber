Magento modul Osobní Odběr
==========================

Modul přidává do Magento dodací metodu - **Osobní odběr**

Osobní odběr umožňuje obchodníkovi použít cenový model pro výpočet ceny za osobní odběr zákazníkem na pobočce.

## Nastavení a použití modulu

### Nastavení v backendu Magenta

V konfiguraci v sekci _Systém > Nastavení > Dodací metody - Osobní odběr_ (System > Configuration > Shipping Methods - Personal taking) je možné nastavit:

<table>
<tbody>
<tr>
  <td> Povoleno (Enabled) </td>
  <td> Povolí a nebo zakáže použití osobního odběru během vytváření objednávky </td>
</tr>
<tr>
  <td> Název (Title) </td>
  <td> Název dodací metody zobrazený v nákupním košíku. </td>
</tr>
<tr>
  <td> Název metody (Method name) </td>
  <td> Popis výpočtu pro osobní odběr. Je zobrazeno v pokladně společně s názvem (Title) a celkovou účtovanou cenou.</td>
</tr>
<tr>
  <td> Typ (Type) </td>
  <td> Nastavení modelu pro výpočet ceny za osobní odběr: 
    <ul>
      <li><em>Není (None)</em> - Vypne výpočet a metoda je nabídnuta zdarma. </li>  
      <li><em>Za položku (Per item)</em> - Aplikuje sazbu na každou položku v košíku. </li>  
      <li><em>Za každou objednávka (Per order)</em> - Aplikuje sazbu na každý košík objednávky (při dodání na více adres). </li>  
    </ul>
  </td>
</tr>
<tr>
  <td> Sazba (Price) </td>
  <td> Sazba použitá pro výpočet ceny dodací metody. </td>
</tr>
<tr>
  <td> Výpočet manipulačního poplatku (Calculate handling fee) </td>
  <td> Nastavení manipulačního poplatku za použití osobního odběru:
    <ul>
      <li><em>Fixní (Fixed)</em> - Poplatek je pevná částka. </li>
      <li><em>Percentuálě (Percent)</em> - Poplatek je vypočten jako procento z celkové ceny objednávky. </li>
    </ul>
  </td>
</tr>
<tr>
  <td> Poplatek (Handling fee) </td>
  <td> Cena poplatku za manipulaci, která je přidána k celkové ceně za dodání. Manipulační poplatek může být fixní a nebo percentuální. </td>
</tr>
<tr>
  <td> Zobrazená chybová hláška (Displayed error message) </td>
  <td> Chybová hláška zobrazená pokud osobní odběr není z jakéhokoliv důvodu dostupný.</td>
</tr>
<tr>
  <td> Použitelné ve státech (Ship to Applicable Countries) </td>
  <td> Specifikujte státy, ve kterých je možné osobní odběr použít.
    <ul>
      <li><em>Všechny povolené země (All Allowed Countries)</em> - Všechny povolené země mohou zobrazit osobní odběr. Nastavení povolených zemí v je obecné konfiguraci (General configuration).</li>
      <li><em>Vybrané země (Specific Countries)</em> - Použití osobního odběru je omezeno na země vybrané v Doručovat do těchto zemí (Ship to Specific Countries) viz níže.</li>
    </ul>
  </td>
</tr>
<tr>
  <td>Doručovat do těchto zemí (Ship to Specific Countries)</td>
  <td>Vyberte země, které mohou nabídnou osobní odběr. Tento seznam je použit pouze v případě, že Použitelné ve státech (Ship to Applicable Countries) je nastaveno na Vybrané země (Specific Countries)</td>
</tr>
<tr>
  <td>Pořadí (Sord Order)</td>
  <td>Nastavení požadí zobrazení osobního odběru. Tato hodnota je relativní vůči nastavení ostatních dodacích metod. Řazení je v vzestupné.</td>
</tr>
</tbody>
</table>

## Testováno na

 - Magento CE 1.9.0.1

Na verzích nižších než 1.9.0.1 nebylo zatím testováno, na 99% bude fungovat ve všech verzích 1.x

## Podpora

Veškeré dotazy a hlášení chyb směřujte na https://github.com/magentocz/osobniodber/issues

# LICENCE

    Open Software License (OSL 3.0)

    /** 
    * Magento CZ Module
    * 
    * NOTICE OF LICENSE 
    * 
    * This source file is subject to the Open Software License (OSL 3.0) 
    * that is bundled with this package in the file LICENSE.txt. 
    * It is also available through the world-wide-web at this URL: 
    * http://opensource.org/licenses/osl-3.0.php 
    * If you did of the license and are unable to 
    * obtain it through the world-wide-web, please send an email 
    * to magentocz@gmail.com so we can send you a copy immediately. 
    * 
    * @copyright Copyright (c) 2014 GetReady s.r.o. (https://getready.cz)
    *
    */


[![Analytics](https://ga-beacon.appspot.com/UA-54971165-2/magentocz/osobniodber/README?pixel)](https://github.com/igrigorik/ga-beacon)

