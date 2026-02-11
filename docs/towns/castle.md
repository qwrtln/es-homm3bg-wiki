# Castillo

## Edificios

=== "Vacío"

    <figure markdown="span">
        ![Castillo Vacío](../assets/towns-castle-empty.webp){ width="680" align=right }
    </figure>

=== "Fully Built"

    <figure markdown="span">
        ![Castillo Totalmente Construido](../assets/towns-castle-full.webp){ width="680" align=right }
    </figure>

=== "Back Side"

    <figure markdown="span">
        ![Lado Trasero de Castillo](../assets/towns-castle-back.webp){ width="680" align=right }
    </figure>

| Nombre | Coste de Construcción | Efecto |
| :--- | ---: | :---: |
| Alcaldía | 10 :gold:<br>4 :building_materials:<br>0 :valuables: | Al inicio de cada ronda de Recursos, elige:<br>:instant: 5 :gold:<br><br>— O —<br><br>:instant: +1:movement: |
| Ciudadela | 8 :gold:<br>5 :building_materials:<br>1 :valuables: | Permite **Refuerzo** de [unidades](#units). Cuando estás bajo asedio, añade 3 cartas Muros, 1 Puerta, y 1 [Torre de Arqueros](../units/arrow_tower.md) al tablero de Combate. |
| Cofradía de Magos | 4 :gold:<br>2 :building_materials:<br>1 :valuables: | **Cuando se construye:**<br>**Buscar(2)** [:spell:](../spells/index.md) dos veces.<br><br>**Después de construirlo:**<br>Una vez por turno :pay: 6 :gold: para **Buscar(2)** [:spell:](../spells/index.md). |
| Torres | 5 :gold:<br>3 :building_materials:<br>1 :valuables: | Permite **Reclutamiento** de [unidades](#units) de :bronze:. |
| Campos Sagrados | 8 :gold:<br>6 :building_materials:<br>3 :valuables: | Permite **Reclutamiento** de [unidades](#units) de :silver:. |
| Gloria de Erathia | 10 :gold:<br>9 :building_materials:<br>4 :valuables: | Permite **Reclutamiento** de [unidades](#units) de :golden:. |
| Hermandad de la Espada | 8 :gold:<br>4 :building_materials:<br>0 :valuables: | Al inicio de cada ronda de Recursos, gana una :morale_positive:. |
| Herrería | 4 :gold:<br>3 :building_materials:<br>0 :valuables: | Durante tu turno, elige:<br><br>**1.** Retirar una carta de  [:artifact:](../artifacts/index.md) de tu mano para ganar 4 :gold:.<br><br>**2.** :pay: 6 :gold: para **Buscar(2)** [:artifact:](../artifacts/index.md). |


## Héroes

| Name | Class | Ability | Specialty |
| :--- | :--- | :--- | :--- |
| [Adelaide](../heroes/adelaide.md) | :magic: Cleric | [Wisdom](../abilities/wisdom.md) | [Frost Ring](../heroes/adelaide.md#specialty) |
| [Catherine](../heroes/catherine.md) | :might: Knight | [Leadership](../abilities/leadership.md) | [Crusaders](../heroes/catherine.md#specialty) |
| [Ingham](../heroes/ingham.md) | :magic: Cleric | [Mysticism](../abilities/mysticism.md) | [Zealots](../heroes/ingham.md#specialty) |
| [Lord Haart](../heroes/lord_haart_castle.md) | :might: Knight | [Estates](../abilities/estates.md) | [Estates](../heroes/lord_haart_castle.md#specialty) |
| [Tarnum](../heroes/tarnum_castle.md) | :might: Knight | [Artillery](../abilities/artillery.md) | [Ballista](../heroes/tarnum_castle.md#specialty) |
| [Rion](../heroes/rion.md) | :magic: Cleric | [Wisdom](../abilities/wisdom.md) | [Battlefield Medic](../heroes/rion.md#specialty) |
| [Valeska](../heroes/valeska.md) | :might: Knight | [Archery](../abilities/archery.md) | [Marksmen](../heroes/valeska.md#specialty) |


## Unidades

Para la versión "Pocos" y "Manada" de la misma unidad, los cambios de Características se muestran en **negrita**.

| Name | # | Tier | Type | :attack: | :defense: | :health_points: | :initiative: | Recruitment Cost | Abilities |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | ---: | :--- |
| [Halberdiers](../units/halberdiers.md#few) | Few | :bronze: | [:unit_ground:](../units/index.md#ground-units) | 2 | 1 | 2 | 4 | 2 :gold: | - |
| [Halberdiers](../units/halberdiers.md#pack) | Pack | :bronze: | [:unit_ground:](../units/index.md#ground-units) | **3** | 1 | 2 | **5** | 3 :gold: | :unit_passive: |
| [Marksmen](../units/marksmen.md#few) | Few | :bronze: | [:unit_ranged:](../units/index.md#ranged-units) | 2 | 0 | 2 | 4 | 3 :gold: | - |
| [Marksmen](../units/marksmen.md#pack) | Pack | :bronze: | [:unit_ranged:](../units/index.md#ranged-units) | 2 | 0 | 2 | **6** | 5 :gold: | :unit_attack: |
| [Griffins](../units/griffins.md#few) | Few | :bronze: | [:unit_flying:](../units/index.md#flying-units) | 2 | 0 | 4 | 6 | 4 :gold: | :unit_retaliation: |
| [Griffins](../units/griffins.md#pack) | Pack | :bronze: | [:unit_flying:](../units/index.md#flying-units) | **3** | 0 | 4 | **9** | 6 :gold: | :unit_retaliation: |
| [Crusaders](../units/crusaders.md#few) | Few | :silver: | [:unit_ground:](../units/index.md#ground-units) | 3 | 2 | 4 | 5 | 6 :gold: | - |
| [Crusaders](../units/crusaders.md#pack) | Pack | :silver: | [:unit_ground:](../units/index.md#ground-units) | **4** | 2 | 4 | **6** | 10 :gold: | :unit_attack: |
| [Zealots](../units/zealots.md#few) | Few | :silver: | [:unit_ranged:](../units/index.md#ranged-units) | 3 | 1 | 5 | 5 | 8 :gold: | - |
| [Zealots](../units/zealots.md#pack) | Pack | :silver: | [:unit_ranged:](../units/index.md#ranged-units) | **4** | 1 | 5 | **7** | 12 :gold: | :unit_passive: |
| [Champions](../units/champions.md#few) | Few | :golden: | [:unit_ground:](../units/index.md#ground-units) | 5 | 2 | 7 | 7 | 12 :gold: | :map_effect: |
| [Champions](../units/champions.md#pack) | Pack | :golden: | [:unit_ground:](../units/index.md#ground-units) | **6** | 2 | 7 | **9** | 20 :gold:<br>1 :valuables: | :unit_attack: |
| [Archangels](../units/archangels.md#few) | Few | :golden: | [:unit_flying:](../units/index.md#flying-units) | 6 | 3 | 8 | 12 | 20 :gold:<br>1 :valuables: | :unit_passive: |
| [Archangels](../units/archangels.md#pack) | Pack | :golden: | [:unit_flying:](../units/index.md#flying-units) | **7** | 3 | **10** | **18** | 30 :gold:<br>2 :valuables: | :unit_passive: |


## Viene Con

- [Juego Principal](../content/core_game.md)


## Ver También

- [Lista de Ciudades](../towns/index.md)
