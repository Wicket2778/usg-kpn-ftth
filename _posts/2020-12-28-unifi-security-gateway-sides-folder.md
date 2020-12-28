---
title: De sites/default map aanmaken op Unifi controller
date: 2020-12-28 15:00:00 +0100
categories: [Documentatie, Handleiding]
tags: [usg, unifi]
seo:
  date_modified: 2020-12-19 15:51:02 +0100
---

## Inleiding

In de handleidingen op deze site wordt er gevraagd om een json configuratie bestand in een bepaalde map (sites/default) neer te zetten. Mocht je een eigen site hebben aangemaakt dan zal daar, in plaats van default, de naam van je site verschijnen. Deze map bestaat soms niet. In deze handleiding neem ik je mee hoe je deze map kan laten aanmaken door een floorplan aan te maken.

## De sites/default map aanmaken

Eerst gaan we via het map icoon aan de linkerkant naar de floorplan pagina.

Ga naar <kbd>map</kbd> en dan, via <kbd>Topology</kbd>, naar <kbd>Floorplan</kbd>.

![usg_controller_add_new_network](/usg-kpn-ftth/assets/img/usgkpnfolder/usg_map_floorplan.png)

Klik op <kbd>Add new floorplan</kbd> en dan, via <kbd>Choose floorplan image</kbd>, kies je een willekeurige afbeelding van je computer.

![usg_controller_add_new_network](/usg-kpn-ftth/assets/img/usgkpnfolder/usg_floorplan_image.png)

Klik op <kbd>Save</kbd> waarna de afbeelding wordt geupload naar de controller. Op dit moment wordt de afbeelding opgeslagen in de sites map en als deze niet bestaat wordt hij voor ons aangemaakt.

![usg_controller_add_new_network](/usg-kpn-ftth/assets/img/usgkpnfolder/usg_floorplan_save.png)

Wanneer je de floorplan hebt bewaart kan je hem ook weer verwijderen door te kiezen voor <kbd>Edit Floorplans</kbd> en daarna te kiezen voor <kbd>Delete</kbd>

![usg_controller_add_new_network](/usg-kpn-ftth/assets/img/usgkpnfolder/usg_floorplan_delete.png)

Je kan nu verder met de andere handleiding om de gateway.config.json in de controller in de juiste map te plaatsen.
