# FR-1.1.3 – Stofna virka skráningu

<!-- Afritið í requirements/<auðkenni>.md. Haldið ## fyrirsögnum óbreyttum.
Krafa eftir yfirferð og próf eru hér; upphaflegur texti, mat og rökstuðningur í issue.
Afritið ### prófakaflann til að bæta við prófum; gefið hverju prófi nýtt auðkenni. -->

## Auðkenni
FR-1.1.3

## Yfirferðar-issue
<!-- Setjið hér smellanlegan Markdown-tengil á yfirferðar-issue, t.d.:
[Yfirferð kröfunnar – issue #12](https://github.com/HOPUR/SAFN/issues/12)
Skiptið HOPUR, SAFN og 12 út fyrir rétt gildi. Notið heilan tengil;
#12 eitt og sér verður ekki sjálfkrafa að issue-tengli í Markdown-skrá.
Athugasemdin birtist aðeins í frumtexta skrárinnar, ekki í birtri útgáfu. -->
[Yfirferð kröfunnar - issue #9](https://github.com/BaliVeselaj204/HBV301G-Verkefni6/issues/9)

## Uppruni
[FR-1.1.3 í verkefni 1](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/functional_requirement.md#fr-113)

## SRS-staðsetning
1.1 Skráning við komu – [SRS-yfirlit](../SRS-yfirlit.md)

## Krafa eftir yfirferð
Þegar kerfið hefur greint komu ökutækis inn á gjaldsvæði og lesið
skráningarnúmer þess skal kerfið stofna virka talningu með
skráningarnúmerinu, gjaldsvæðinu og komutíma ökutækisins.

## Höfundur
Kristinn Freyr Óskarsson

## Prófunartilvik

### PT-FR-1.1.3-01
**Krafa:** FR-1.1.3
**Tegund:** venjulegt
**Forsendur og upphafsástand:** Gjaldsvæði A er skráð í kerfinu og engin virk talning er til fyrir ökutækið ABC12. Skráningarnúmer ökutækisins er læsilegt.
**Aðgerð eða inntak:** Ökutækinu ABC12 er ekið inn á gjaldsvæði A kl. 10:15. Kerfið greinir komuna og les skráningarnúmerið.
**Vænt niðurstaða:** Ný virk talning er skráð fyrir ABC12 á gjaldsvæði A með komutímann 10:15.
