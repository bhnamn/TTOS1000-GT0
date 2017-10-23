# Feature Branch

Kuvauksen kirjoitti: Niko Valkonen, K2543

## Mitä tarkoittaa Feature Branch?

Feature Branch

Feature Branch on kehittämisessä ja versionhallinnassa käytetty termi ominaisuuden omalle haaralle eli kehityspolulle. Eli kun ominaisuudelle luodaan oma kehityspolku muiden polkujen muutokset eivät vaikuta ominaisuuden kehityspolkuun
Ja kun ominaisuudet ovat valmiita ne voidaan liittää mergellä päähaaraan.

## Esimerkkejä
Case 1: Matti rupeaa rakentamaan ominaisuutta ja ei luo ominaisuudelle kehityspolkua ja koodaa 900 riviä koodia  -> tekee commitin. 
Samaan aikaan Maija koodaa toiseen ominaisuuteen muutoksia jolla ei ole omaa kehityspolkua ja committaa Matin jälkeen -> matin muutokset poistuu

Case 2: Jaska rakentaa uutta ominaisuutta tuotteeseen X ja muistaa ominaisuudelle luoda oman kehityspolun. Hän committaa -> muutokset vaikuttavat vain tähän kehityshaaraan.
Samaan aikaan Keijo tekee muutoksia toiseen kehityspolkuun ja committaa -> ei muutoksia Jaskan työhön.

## Linkkejä

* [Git - Linux.fi](https://www.linux.fi/wiki/Git#Haarat)
* [Workflow for Git feature branching - Atlassian Documentation](https://confluence.atlassian.com/bitbucket/workflow-for-git-feature-branching-814201830.html)

## Linkit wikin muihin sivuihin
* [Jatkuva Integraatio](https://github.com/JAMKPROJ/TTOS1000-GT0/blob/master/jatkuva-integraatio.md)
