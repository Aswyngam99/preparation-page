<template>
     <div>
        <Navigation/>
      <v-card tile class="back" height="200">
      </v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">1. Objet</h2>
                <p>Cette procédure décrit les étapes a suivre pour préparer le réactif indicateur mixte.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire Henkel Reghaia.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle class="text-wrap">Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle class="text-wrap">Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle class="text-wrap">Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>/</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse. <br> Le responsable laboratoire est responsable sur la validation des méthodes. </p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
            <h2 class="titre">6. Processus</h2>
                <v-list-item>
                <v-list-item-content>
                <v-list-item-title><em> <u> <strong> Preparation des reactifs </strong> </u></em></v-list-item-title>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>1. Preparation solution mère de l’indicateure mixte :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 1g de bromure de duminium dans un becher 50ml, 0.5g de bleu disulfine dans un autre becher de 50ml et ajouter 20 à 30ml d’une solution d’ethanol à 10% v/v. <br> Ajouter les solutions dans une fiole jaugee de 500ml. rincer les bechers avec la solution d’ethanol introduire le liquide de rinçage dans la fiole jaugee puis ajustes au volume avec une solution d’éthanol à 10% v/v.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>2. Preparation solution de l’indicateure mixte :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Ajouter 40ml de solution mère dans un becher 200ml d’eau . dans une fiole jaugee a 1000ml . ajouter 40ml de l’acide sulfurique 5N et ajuster au volume de l’eau distillée.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>3. Preparation solution de Thiosulfate de sodium 0.1N :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">En prend un volume 100ml de thiossulfate de sodium 1N et diluee jusqua 1000ml avec l’eau distillée.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>4.Preparation solution de H<sub>2</sub>So<sub>4</sub>5N :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">En prend un volume de 139.5ml de H<sub>2</sub>So<sub>4</sub> a 96% et diluee avec l’eau distile jusqua 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>5.Preparation solution de H<sub>2</sub>So<sub>4</sub>1N :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">En prend un volume de 27ml de H<sub>2</sub>So<sub>4</sub> à 96% etdiluee avec l’eau distiles jusqua 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>6. Preparation solution de potassium Iodée KI 10% v/v</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 100g de kI à 100% et diluee avec l’eau distillée jusqu’a 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>7. Preparation solution d’acide citrique 1N :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 210g de C<sub>6</sub>H<sub>6</sub>O<sub>7</sub>.H<sub>2</sub>O (99.5%-101%) et completer jusqua 1000ml avec l’eau distillée.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>8. Preparation solution de NaoH 10% m/m :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 100g de NaoH à( 98% 100%) et completer jusqua 1000ml avec l’eau distillée.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>9. Preparation soluton de H<sub>2</sub>O<sub>2</sub> 10% v/v :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">En prend un volume 100ml de H<sub>2</sub>O<sub>2</sub> à ( 30.31%) et diluee avec l’eau distile jusqua 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>10. Preparation solution de EDTA à 0.1N :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 37.6g de EDTA à 99% et completer avec l’eau distile jusqua 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>11. preparation d’une solution tampon pH : 10 :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">peser 70g de chlorure dammonium à 99%. le dissoudre dans 200ml d’eau distillée. Ajouter 570ml de solution amoniacal de densite 0.89 completer a 1000ml avec l’eau distillée</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>12. preparation solution de phénophtaline :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">peser 1g de phenophtaline de (99%-101%) et completer à 100ml avec l’eau distillée.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>13. preparation solution l’ethanol à 60% :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">en prend un volume 625ml de l’ethanol 96% et completer avec l’eau distillée jusqua 1000 ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>14. Hyamine 0.005M :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 11.2g de hyamine 1622 dans une fiole 5000ml bien ; completer avec de l’eau distillée, agitation pendant 30mn.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>15. sodium dodecyle sulfate  0.005 M :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 1.4565g de de sodium dodecyle sulfate (99%) et complete avec l’eau distillée jusqua 1000ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><em> <u> <strong>Calcul facteur de correction hyamine :</strong> </u></em></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">F=10/Vhyamine</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><strong>Preparation solution de NaoH 30% :</strong></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">en prend un volume de 67ml de NaoH 45% et completer avec l’eau distillée jusqua 100ml.</v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap"><strong>preparation solution de potassium chloride KCL 3M :</strong></v-list-item-subtitle>
                <v-list-item-subtitle class="text-wrap">Peser 224g de potassium chloride et completer jusqua 1000ml avec l’eau distillée.</v-list-item-subtitle>
                </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
              <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                    <h2 class="titre">7. Annexes</h2>
                 <v-simple-table>
                    <template v-slot:default>
                        <thead>
                            <tr>
                                <th class="text-left white--text tab"> Enregistrement </th>
                                <th class="text-left white--text tab"> Code </th>
                                <th class="text-left white--text tab"> Localisation </th>
                                <th class="text-left white--text tab"> Support </th>
                                <th class="text-left white--text tab"> Durée de conservation </th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr v-for="item in things" :key="item.Enregistrement">
                                <td>{{ item.Enregistrement }}</td>
                                <td>{{ item.Code }}</td>
                                <td>{{ item.Localisation }}</td>
                                <td>{{ item.Support }}</td>
                                <td>{{ item.Durée}}</td>
                            </tr>
                        </tbody>
                    </template>
                </v-simple-table>
                </v-card-text>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
         things: [
          {
            Enregistrement: 'Fiche de suivi incident qualité',
            Code: 'SD SHEQ TNC 4.3.12-10',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          }
        ]

    }),
  }
</script>
<style scoped>
.confirm-card {
  overflow: hidden;
}
.titre{
    color: #ff0011;
}
.back{
    background: url('../../public/labo3.jpg');
}
.tab{
  background-color: #fa3722;
}
</style>