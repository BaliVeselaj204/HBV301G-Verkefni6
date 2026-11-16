# FR-1.2.2 – Finna virka skráningu við brottför

## Auðkenni
FR-1.2.2

## Yfirferðar-issue
[Yfirferð kröfunnar - issue #11](https://github.com/BaliVeselaj204/HBV301G-Verkefni6/issues/11)

## Uppruni
[FR-1.2.2](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/functional_requirement.md#fr-122)

## SRS-staðsetning
1.2 Skráning við brottför – [SRS-yfirlit](../SRS-yfirlit.md)

## Krafa eftir yfirferð
Þegar ökutæki yfirgefur gjaldsvæði skal kerfið lesa skráningarnúmer
ökutækisins og finna virku talninguna sem samsvarar því númeri.

## Höfundur
Kristinn Freyr Óskarsson

## Prófunartilvik

### PT-FR-1.2.2-01
**Krafa:** FR-1.2.2
**Tegund:** venjulegt
**Forsendur og upphafsástand:** Ökutækið ABC12 er á gjaldsvæði A og á virku talninguna T-101. Skráningarnúmer ökutækisins er læsilegt
**Aðgerð eða inntak:** Ökutækinu ABC12 er ekið út af gjaldsvæði A
**Vænt niðurstaða:** Kerfið les skráningarnúmerið ABC12 og finnur virku talninguna T-101.

### PT-FR-1.2.2-02
**Krafa:** FR-1.2.2
**Tegund:** jaðartilvik
**Forsendur og upphafsástand:** Ökutækið ABC12 er á gjaldsvæði A. Fyrir ABC123 eru til tvær talningar á svæðinu. T-100 er lokið og T-101 er virk. Skráningarnúmer ökutækisins er læsilegt.
**Aðgerð eða inntak:** Ökutækinu ABC12 er ekið út af gjaldsvæði A.
**Vænt niðurstaða:** Kerfið les skráningarnúmerið ABC12 og velur virku talninguna T-101 úr þeim tveimur talningum sem til eru.
