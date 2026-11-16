# FR-2.1.1 – Reikna lengd stæðistíma

## Auðkenni
FR-2.1.1

## Yfirferðar-issue
[Yfirferð kröfunnar - issue #14](https://github.com/BaliVeselaj204/HBV301G-Verkefni6/issues/14)

## Uppruni
[FR-2.1.1 í verkefni 1](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/functional_requirement.md#fr-211)

## SRS-staðsetning
1.3 Útreikningur stæðistíma – [SRS-yfirlit](../SRS-yfirlit.md)

## Krafa eftir yfirferð
Kerfið skal reikna lengd stæðistíma út frá þeim tíma sem líður frá skráðum komutíma til skráðs brottfarartíma í sömu talningu.

## Höfundur
Kristinn Freyr Óskarsson

## Prófunartilvik

### PT-FR-2.1.1-01
**Krafa:** FR-2.1.1
**Tegund:** venjulegt
**Forsendur og upphafsástand:** Talningu T-101 er lokið. Skráður komutími er kl 11:30 og skráður brottfarartími er kl 11:45 sama dag.
**Aðgerð eða inntak:** Stæðistími fyrir T-101 er reiknaður út.
**Vænt niðurstaða:** Reiknaður stæðistími fyrir T-101 er 15 mínútur.

### PT-FR-2.1.1-02
**Krafa:** FR-2.1.1
**Tegund:** jaðartilvik
**Forsendur og upphafsástand:** Talningu T-102 er lokið. Skráður komutími er kl. 23:50 og skráður brottfarartími er kl. 00:10 daginn eftir.
**Aðgerð eða inntak:** Stæðistími fyrir T-102 er reiknaður út.
**Vænt niðurstaða:** Reiknaður stæðistími fyrir T-102 er 20 mínútur.
