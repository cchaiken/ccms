---
title: Testimonials
id: testimonials
intro:
  main: Testimonials
  style: plain
newsletter: true
testimonials:
  voice:
  - name: Jane Voice
    avatar: testimonial-avatar.jpg
    text:
    - Magnus es, domine, et laudabilis valde magna virtus tua, et sapientiae tuae
      non est numerus. et laudare te vult homo, aliqua portio creaturae tuae, et homo
      circumferens mortalitem suam, circumferens testimonium peccati sui et testimonium,
      quia superbis resistis et tamen laudare te vult homo, aliqua portio creaturae
      tuae.
  - name: John Voice
    avatar: testimonial-avatar.jpg
    text:
    - Et quomodo invocabo deum meum, deum et dominum meum, quoniam utique inme ipsum
      eum invocabo, cum invocabo eum? et quis locus est in me, quoveniat in me deus
      meus? quo deus veniat in me, deus, qui fecit caelum et terram?
  piano:
  - name: Joan Piano
    avatar: testimonial-avatar.jpg
    text:
    - Capiunt ergone te caelum et terra, quoniam tu imples ea? an imples et restat,
      quoniam non te capiunt? et quo refundis quidquid impleto caeloet terra restat
      ex te? an non opus habes, ut quoquam continearis, qui contines omnia, quoniam
      quae imples continendo imples?
    - Non enim vasa, quae te plena sunt, stabilem te faciunt, quia etsi frangantur
      non effunderis.
  - name: Jim Piano
    avatar: testimonial-avatar.jpg
    text:
    - Quid est ergo deus meus? quid, rogo, nisi dominus deus? quis enim dominus praeter
      dominum? aut quis deus praeter deum nostrum? summe, optime, potentissime, omnipotentissime,
      misericordissime et iustissime, secretissime et praesentissime, pulcherrime
      et fortissime,stabilis et inconprehensibilis, inmutabilis, mutans omnia, numquam
      novus, numquam vetus, innovans omnia.
  performance:
  - name: Judy Performance
    avatar: testimonial-avatar.jpg
    text:
    - Sed tamen sine me loqui apud misericordiam tuam, me terram et cinerem,sine tamen
      loqui, quoniam ecce misericordia tua est, non homo, inrisormeus, cui loquor.
      et tu fortasse inrides me, sed conversus misereberismei. quid enim est quod
      volo dicere, domine, nisi quia nescio, unde venerim huc, in istam, dico vitam
      mortalem, an mortalem vitalem? nescio. et susceperunt me consolationes miserationum
      tuarum, sicut audivi a parentibus carnis meae, ex quo et in qua me formasti
      in tempore; non enim ego memini.
  - name: Job Performance
    avatar: testimonial-avatar.jpg
    text:
    - Exaudi, deus. vae peccatis hominum! et homo dicit haec, et misereris eius, quoniam
      tu fecisti eum et peccatum non fecisti in eo. quis me commemorat peccatum infantiae
      meae, quoniam nemo mundus a peccato coram te, nec infans, cuius est unius diei
      vita super terram? quis me commemorat? an quilibet tantillus nunc parvulus,
      in quo video quod non memini de me?
  idol:
  - name: Jennifer Idol
    avatar: testimonial-avatar.jpg
    text:
    - Nonne ab infantia huc pergens veni in pueritiam? vel potius ipsa in me venit
      et successit infantiae? nec discessit illa quo enim abiit? et tamen iam non
      erat.
    - Non enim eram infans, qui non farer, sed iam puer loquens eram. et memini hoc,
      et unde loqui didiceram, post adverti. non enim docebant me maiores homines,
      praebentes mihi verba certo aliquo ordine doctrinae sicut paulo post litteras,
      sed ego ipse mente, quam dedisti mihi, deus meus, cum gemitibus et vocibus variis
      et variis membrorum motibus edere vellem sensa cordis mei, ut voluntati pareretur
  - name: Julian Idol
    avatar: testimonial-avatar.jpg
    text:
    - Deus, deus meus, quas ibi miserias expertus sum et ludificationes, quandoquidem
      recte mihi vivere puero id proponebatur, obtemperare monentibus, ut in hoc saeculo
      florerem, et excellerem linguosis artibus, ad honorem hominum et falsas divitias
      famulantibus. inde in scholam datus sum, ut discerem litteras, in quibus quid
      utilitatis esset ignorabam miser. et tamen, si segnis in discendo essem, vapulabam.
---

Over the years I’ve taught the magic of music to Marin County children and adults from all walks of life. I'm so grateful for the opportunity to inspire and educate on a daily basis. Watching you blossom into your fullest potential makes my heart sing!

Here's what my students are saying about their music lessons.

## Voice Lessons

{% for each in page.testimonials.voice %}
{% include testimonial-card.html testimonial=each %}
{% endfor %}

## Piano Lessons

{% for each in page.testimonials.piano %}
{% include testimonial-card.html testimonial=each %}
{% endfor %}

## Performance Coaching

{% for each in page.testimonials.performance %}
{% include testimonial-card.html testimonial=each %}
{% endfor %}

## Marin Idol

{% for each in page.testimonials.idol %}
{% include testimonial-card.html testimonial=each %}
{% endfor %}

## Try a free lesson!

Why not find out for yourself? If you are interested in Voice or Piano lessons I offer [free introductory lessons]({{ '/contact/' | relative_url }}).