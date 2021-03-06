# LikeBox hardware

## Boitier

### Fourniture

Le boitier est composé de plaques de Plexiglass 250 x 200 x 8 mm 
disponible aux dimensions avec bords polis sur http://www.plastiquesurmesure.com/ [Plaque PMMA Coule Incolore Transparent Brillant 8mm](http://www.plastiquesurmesure.com/materiaux-plastiques-1/plaque/plaque-pmma-coule-incolore-transparent-brillant-8-mm.html)

~ 40€ pour deux plaques. 

### Préparation
Les plans de découpe peuvent être collés sur les plaques dont on conserve le film de protection jusqu'au montage final.

Les passages de cables sont percés à la mêche de charpentier avec une perceuse sur colonne à vitesse lente. Percer avec un martyr ou par les deux faces pour éviter un éclatement du plexiglass à la sortie de la mêche.

Les trous de fixation sont percés en 2mm avec une mêche à métaux, puis un filetage est créé au taraud de 2.8mm

## Raspberry Pi

Une Raspberry 1ère génération suffit pour la box de base. Pour utiliser la sortie HDMI une 2nde génération a nettement plus de ressources.

~ 50€

## Boutons

http://fr.farnell.com/itw-switches/76-9450-439088g/commutateur-vert-domed/dp/241519

http://fr.farnell.com/itw-switches/76-9450-439088r/commutateur-rouge-domed/dp/241520

## Ecran

http://www.ebay.com/itm/Blue-Serial-IIC-I2C-TWI-2004-204-20X4-Character-LCD-Module-Display-For-Arduino/181299099752

## Module RTC

module "Tiny RTC" I2C à base de DS1307 - attention, ce module utilise une pile bouton lithium rechargeable, autant le commander avec sa pile. 
http://www.ebay.fr/itm/Real-Time-Clock-Module-I2C-RTC-DS1307-AT24C32-Battery-UK-/181812257370?hash=item2a54dae25a

## câblage etc

Nous avons fonctionné un bon moment avec des connecteurs de platine de test, mais pour éviter les erreurs de branchement, comme d'inverser les boutons (sic), une nappe est une solution propre et pas chère :
http://www.ebay.com/itm/GPIO-Ribbon-Cable-for-Raspberry-Pi-10cm-15cm-30cm-50cm-Rainbow-Grey-/141181560531?var=440250034003&hash=item20df13a6d3

Prise de debug RS232

## Wifi

Les likebox peuvent fonctionner en autonome si un résau Wifi est disponible
Après de mauvaises surprise nous recommandons une clé Wifi supportée our-of-the-box par le noyeau, avec un chipset courant, comme par exemple : http://www.materiel.net/reseau/tp-link-cle-usb-wifi-tl-wn823n-94768.html

## Pieds

support de fixation http://www.bax-shop.fr/dap-outer-adaptor-35mm-diametre-180-x-120mm-plastique.html 
trépied enceinte http://www.bax-shop.fr/innox-iva-s-1-pied-d-enceinte-version-medium-1-80m.html

## Alimentation

- Alimentation par transformateur USB. Nous avons fait passer le fix dans le tube du trepied, attention à prendre un chargeur USB avec un loooong fil.
- Alimentation par batterie



