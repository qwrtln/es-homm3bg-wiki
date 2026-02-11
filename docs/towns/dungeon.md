# Mazmorra

## Edificios

=== "Vacío"

    <figure markdown="span">
        ![Mazmorra Vacía](../assets/towns-dungeon-empty.webp){ width="680" align=right }
    </figure>

=== "Fully Built"

    <figure markdown="span">
        ![Mazmorra Totalmente Construida](../assets/towns-dungeon-full.webp){ width="680" align=right }
    </figure>

=== "Back Side"

    <figure markdown="span">
        ![Reverso de Mazmorra](../assets/towns-dungeon-back.webp){ width="680" align=right }
    </figure>

| Nombre | Coste de Construcción | Efecto |
| :--- | ---: | :---: |
| Alcaldía | 10 :gold:<br>4 :building_materials:<br>0 :valuables: | Al comienzo de cada ronda de Recursos, elige::<br>:instant: 5 :gold:<br><br>— O —<br><br>:instant: 1 :valuables: |
| Ciudadela | 8 :gold:<br>5 :building_materials:<br>1 :valuables: | Permite **Reforzar** [unidades](#units). Cuando estés bajo asedio, añade 3 cartas de Muralla, 1 de Puerta y 1 de [Torre Flechas](../units/arrow_tower.md) al tablero de Combate. |
| Cofradía de Magos | 4 :gold:<br>2 :building_materials:<br>1 :valuables: | **Cuando se construye:**<br>**Buscar(2)** [:spell:](../spells/index.md) dos veces.<br><br>**Después de construirse:**<br>Una vez por turno :pay: 5 :gold: para **Buscar(2)** [:spell:](../spells/index.md). |
| Madrigueras | 5 :gold:<br>3 :building_materials:<br>1 :valuables: | Permite **Reclutar** [unidades](#units) de :bronze:. |
| Laberintos Internos | 8 :gold:<br>6 :building_materials:<br>3 :valuables: | Permite **Reclutar** [unidades](#units) de :sylver:. |
| Guaridas Antiguas | 10 :gold:<br>9 :building_materials:<br>4 :valuables: | Permite **Reclutar** [unidades](#units) de :golden:. |
| Portal de Invocación | 7 :gold:<br>3 :building_materials:<br>1 :valuables: | Al principio de tu turno, puedes robar 1 carta de [Unidad Neutral](../units/index.md) de los mazos correspondientes a las Viviendas de tu Ciudad y :pay: el coste de Reclutamiento para **Reclutar** esta [unidad].(../units/index.md). |
| Vórtice de Maná | 6 :gold:<br>4 :building_materials:<br>1 :valuables: | Al principio de tu turno, descarta 1 carta de tu mano para barajar tu pila de descartes de nuevo en tu mazo de Poder y Magia. Luego **Busca(3)** en el. |


## Héroes

| Name | Class | Ability | Specialty |
| :--- | :--- | :--- | :--- |
| [Alamar](../heroes/alamar.md) | :magic: Warlock | [Wisdom](../abilities/wisdom.md) | [Resurrection](../heroes/alamar.md#specialty) |
| [Deemer](../heroes/deemer.md) | :magic: Warlock | [Scouting](../abilities/scouting.md) | [Meteor Shower](../heroes/deemer.md#specialty) |
| [Jeddite](../heroes/jeddite.md) | :magic: Warlock | [Sorcery](../abilities/sorcery.md) | [Mysterious Warlock](../heroes/jeddite.md#specialty) |
| [Lorelei](../heroes/lorelei.md) | :might: Overlord | [Scouting](../abilities/scouting.md) | [Harpies](../heroes/lorelei.md#specialty) |
| [Mutare](../heroes/mutare.md) | :might: Overlord | [Tactics](../abilities/tactics.md) | [Dragons](../heroes/mutare.md#specialty) |
| [Sephinroth](../heroes/sephinroth.md) | :magic: Warlock | [Intelligence](../abilities/intelligence.md) | [Valuables](../heroes/sephinroth.md#specialty) |
| [Tarnum](../heroes/tarnum_dungeon.md) | :might: Overlord | [Estates](../abilities/estates.md) | [Dragons](../heroes/tarnum_dungeon.md#specialty) |


## Unidades

Para la versión "Pocos" y "Manada" de la misma unidad, los cambios de Características se muestran en **negrita**.

| Name | # | Tier | Type | :attack: | :defense: | :health_points: | :initiative: | Recruitment Cost | Abilities |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | ---: | :--- |
| [Troglodytes](../units/troglodytes.md#few) | Few | :bronze: | [:unit_ground:](../units/index.md#ground-units) | 2 | 1 | 2 | 4 | 2 :gold: | - |
| [Troglodytes](../units/troglodytes.md#pack) | Pack | :bronze: | [:unit_ground:](../units/index.md#ground-units) | **3** | 1 | 2 | **5** | 3 :gold: | :unit_passive: |
| [Harpies](../units/harpies.md#few) | Few | :bronze: | [:unit_flying:](../units/index.md#flying-units) | 2 | 0 | 3 | 6 | 3 :gold: | :unit_attack: |
| [Harpies](../units/harpies.md#pack) | Pack | :bronze: | [:unit_flying:](../units/index.md#flying-units) | **3** | 0 | 3 | **9** | 5 :gold: | :unit_attack: |
| [Evil Eyes](../units/evil_eyes.md#few) | Few | :bronze: | [:unit_ranged:](../units/index.md#ranged-units) | 3 | 0 | 3 | 5 | 4 :gold: | - |
| [Evil Eyes](../units/evil_eyes.md#pack) | Pack | :bronze: | [:unit_ranged:](../units/index.md#ranged-units) | 3 | **1** | 3 | **7** | 6 :gold: | :unit_passive: |
| [Medusas](../units/medusas.md#few) | Few | :silver: | [:unit_ranged:](../units/index.md#ranged-units) | 3 | 1 | 4 | 5 | 6 :gold: | :unit_passive: |
| [Medusas](../units/medusas.md#pack) | Pack | :silver: | [:unit_ranged:](../units/index.md#ranged-units) | **4** | 1 | 4 | **6** | 12 :gold: | :unit_passive: :unit_retaliation: |
| [Minotaurs](../units/minotaurs.md#few) | Few | :silver: | [:unit_ground:](../units/index.md#ground-units) | 4 | 2 | 4 | 6 | 8 :gold: | :unit_attack: |
| [Minotaurs](../units/minotaurs.md#pack) | Pack | :silver: | [:unit_ground:](../units/index.md#ground-units) | **5** | 2 | 4 | **8** | 14 :gold: | :unit_attack: |
| [Manticores](../units/manticores.md#few) | Few | :golden: | [:unit_flying:](../units/index.md#flying-units) | 5 | 1 | 6 | 7 | 10 :gold: | - |
| [Manticores](../units/manticores.md#pack) | Pack | :golden: | [:unit_flying:](../units/index.md#flying-units) | 5 | 1 | 6 | **11** | 18 :gold:<br>1 :valuables: | :unit_attack: |
| [Manticores](../units/manticores.md#few-alternate) | Few (Alternate) | :golden: | [:unit_flying:](../units/index.md#flying-units) | 4 | 1 | 7 | 8 | 12 :gold: | :unit_attack: |
| [Manticores](../units/manticores.md#pack-alternate) | Pack (Alternate) | :golden: | [:unit_flying:](../units/index.md#flying-units) | 4 | **2** | 7 | **11** | 18 :gold:<br>1 :valuables: | :unit_passive: |
| [Black Dragons](../units/black_dragons.md#few) | Few | :golden: | [:unit_flying:](../units/index.md#flying-units) | 6 | 3 | 8 | 11 | 19 :gold:<br>1 :valuables: | :unit_passive: |
| [Black Dragons](../units/black_dragons.md#pack) | Pack | :golden: | [:unit_flying:](../units/index.md#flying-units) | **8** | 3 | 8 | **15** | 33 :gold:<br>2 :valuables: | :unit_passive: |


## Viene Con

- [Juego Principal](../content/core_game.md)


## Ver También

- [Lista de Ciudades](../towns/index.md)
