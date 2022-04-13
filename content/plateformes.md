---
title: "Plateformes"
date: 2022-04-13T10:44:47+02:00
draft: false
menu: main
weight: 3
---





{{< rawhtml >}}
<h3> Onglets"</h3>
<div class="fr-tabs">
    <ul class="fr-tabs__list" role="tablist" aria-label="[A modifier | nom du système d'onglet]">
        <li role="presentation">
            <button id="tabpanel-404" class="fr-tabs__tab fr-fi-checkbox-line fr-tabs__tab--icon-left" tabindex="0" role="tab" aria-selected="true" aria-controls="tabpanel-404-panel">Label Tab 1</button>
        </li>
        <li role="presentation">
            <button id="tabpanel-405" class="fr-tabs__tab fr-fi-checkbox-line fr-tabs__tab--icon-left" tabindex="-1" role="tab" aria-selected="false" aria-controls="tabpanel-405-panel">Label Tab 2</button>
        </li>
        <li role="presentation">
            <button id="tabpanel-406" class="fr-tabs__tab fr-fi-checkbox-line fr-tabs__tab--icon-left" tabindex="-1" role="tab" aria-selected="false" aria-controls="tabpanel-406-panel">Label Tab 2</button>
        </li>
    </ul>
    <div id="tabpanel-404-panel" class="fr-tabs__panel fr-tabs__panel--selected" role="tabpanel" aria-labelledby="tabpanel-404" tabindex="0">
        <!-- données de test -->
       <p>Contenu 1</p>
    </div>
    <div id="tabpanel-405-panel" class="fr-tabs__panel" role="tabpanel" aria-labelledby="tabpanel-405" tabindex="0">
        <!-- données de test -->
        <p>Contenu 2</p>
    </div>
    <div id="tabpanel-406-panel" class="fr-tabs__panel" role="tabpanel" aria-labelledby="tabpanel-406" tabindex="0">
        <!-- données de test -->
        <p>Contenu 3</p>
    </div>
</div>


<! ----- Tuile ----->
<!-- Tuiles verticales dans la grille -->
<h3> tuiles verticales </h3>
<!-- Tuiles verticales placées dans la grille -->

<div class="fr-grid-row fr-grid-row--gutters">
    <div class="fr-col-6 fr-col-md-4 fr-col-lg-3">
        <div class="fr-tile fr-enlarge-link fr-tile--horizontal-md">
            <div class="fr-tile__body">
                <h4 class="fr-tile__title">
                    <a class="fr-tile__link" href>Titre MD bold</a>
                </h4>
                <p class="fr-tile__desc">Lorem [...] elit ut.</p>
            </div>
            <div class="fr-tile__img">
                <img src="../img/placeholder.1x1.png" class="fr-responsive-img" alt="">
                <!-- L'alternative de l'image (attribut alt) doit à priori rester vide car l'image est illustrative et ne doit pas être restituée aux technologies d’assistance. Vous pouvez toutefois remplir l'alternative si vous estimer qu'elle apporte une information essentielle à la compréhension du contenu non présente dans le texte -->
            </div>
        </div>
    </div>
    <div class="fr-col-6 fr-col-md-4 fr-col-lg-3">
       <div class="fr-tile fr-enlarge-link fr-tile--horizontal-md">
            <div class="fr-tile__body">
                <h4 class="fr-tile__title">
                    <a class="fr-tile__link" href>Titre M bold</a>
                </h4>
                <p class="fr-tile__desc">Lorem [...] elit ut.</p>
            </div>
            <div class="fr-tile__img">
                <img src="../img/placeholder.1x1.png" class="fr-responsive-img" alt="">
                <!-- L'alternative de l'image (attribut alt) doit à priori rester vide car l'image est illustrative et ne doit pas être restituée aux technologies d’assistance. Vous pouvez toutefois remplir l'alternative si vous estimer qu'elle apporte une information essentielle à la compréhension du contenu non présente dans le texte -->
            </div>
        </div>
    </div>
    <div class="fr-col-6 fr-col-md-4 fr-col-lg-3">
        <div class="fr-tile fr-enlarge-link fr-tile--horizontal-md">
            <div class="fr-tile__body">
                <h4 class="fr-tile__title">
                    <a class="fr-tile__link" href>Titre M bold</a>
                </h4>
                <p class="fr-tile__desc">Lorem [...] elit ut.</p>
            </div>
            <div class="fr-tile__img">
                <img src="../img/placeholder.1x1.png" class="fr-responsive-img" alt="">
                <!-- L'alternative de l'image (attribut alt) doit à priori rester vide car l'image est illustrative et ne doit pas être restituée aux technologies d’assistance. Vous pouvez toutefois remplir l'alternative si vous estimer qu'elle apporte une information essentielle à la compréhension du contenu non présente dans le texte -->
            </div>
        </div>
    </div>
    <div class="fr-col-6 fr-col-md-4 fr-col-lg-3">
        <div class="fr-tile fr-enlarge-link fr-tile--horizontal-md">
            <div class="fr-tile__body">
                <h4 class="fr-tile__title">
                    <a class="fr-tile__link" href>Titre M bold</a>
                </h4>
                <p class="fr-tile__desc">Lorem [...] elit ut.</p>
            </div>
            <div class="fr-tile__img">
                <img src="../img/placeholder.1x1.png" class="fr-responsive-img" alt="">
                <!-- L'alternative de l'image (attribut alt) doit à priori rester vide car l'image est illustrative et ne doit pas être restituée aux technologies d’assistance. Vous pouvez toutefois remplir l'alternative si vous estimer qu'elle apporte une information essentielle à la compréhension du contenu non présente dans le texte -->
            </div>
        </div>
    </div>
</div>

{{< /rawhtml >}}
