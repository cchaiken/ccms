---
title: Testimonials
id: testimonials
intro:
  main: Testimonials
  style: plain
newsletter: true
testimonials:
  voice:
  - name: Emily H, Kentfield
    avatar: testimonial-avatar.jpg
    text:
    - I came to Caylia after years of vocal training. She is  a dream. She helped
      me to retrain my voice so that I sang in an organic way, allowing my body to
      simply click into place. I am thrilled to be learning from her.
  - name: Faryn V, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - "I am 9 years old and I take voice lessons from Caylia. \n\nCaylia is a wonderful
      teacher because she improves how you sing and then she improves the things that
      improve what you've improved on. For example she makes me use my belly when
      I sing by having me stand on one foot."
  - name: Sophie B, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - I’ve learned so much from Caylia. She is truly an inspiring teacher. She helped
      me find a voice that I didn’t even know I had.
  - name: Kim W, Marin
    avatar: testimonial-avatar.jpg
    text:
    - I really am enjoying singing in class with you – you’re such a wonderful, resourceful,
      patient, positive teacher.  And really smart and talented, too!
  - name: Renee M, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Caylia has had an incredible impact on my daughter’s singing and professional
      success. She has been both a professional resource in teaching her technique
      and also a personal Coach.
  - name: Paul U, San Anselmo
    avatar: testimonial-avatar.jpg
    text:
    - |-
      Caylia teaches with humor, perfection and persistence.

      She doesn’t seem to force her style on her students but rather explores the natural potential and refines and develops it. Caylia’s passion for the music and her commitment to her students always shines through.
  - name: Danielle W, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - |-
      My daughter has grown into her confidence and coming into her own.

      I’ve also noticed that it’s bled into the rest of her life. She has more confidence in her school performances and presentations. Thank you Caylia!
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