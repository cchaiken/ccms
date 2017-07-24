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
    avatar: avatar-emily-h.jpg
    text:
    - I came to Caylia after years of vocal training. She is  a dream. She helped
      me to retrain my voice so that I sang in an organic way, allowing my body to
      simply click into place. I am thrilled to be learning from her.
  - name: Faryn V, Mill Valley
    avatar: "/uploads/avatar-faryn-v.jpg"
    text:
    - I am 9 years old and I take voice lessons from Caylia.
    - She is a wonderful teacher because she improves how you sing and then she improves
      the things that improve what you've improved on. For example she makes me use
      my belly when I sing by having me stand on one foot.
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
    - Caylia teaches with humor, perfection and persistence.
    - She doesn’t seem to force her style on her students but rather explores the
      natural potential and refines and develops it. Caylia’s passion for the music
      and her commitment to her students always shines through.
  - name: Danielle W, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - My daughter has grown into her confidence and coming into her own.
    - I’ve also noticed that it’s bled into the rest of her life. She has more confidence
      in her school performances and presentations. Thank you Caylia!
  - name: Susan D, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Caylia's heart is in her music and with her students. Our daughter has found
      her voice because of Caylia!
  piano:
  - name: Marie H, San Francisco
    avatar: testimonial-avatar.jpg
    text:
    - With Caylia teaching me, I like playing the piano so much more.
    - I am very happy to have Caylia as my wonderful and gifted teacher.
  - name: Jamie B, Tiburon
    avatar: testimonial-avatar.jpg
    text:
    - In one year my children have learned over fifty songs, chord based accompaniment,
      music theory, and seasonal holiday tunes.
    - She expertly engages my daughters in specific, age-appropriate programs according
      to their interest and ability.
    - She tunes in to the comments my children make to enhance their understanding
      and appreciation of music.
    - I am so thankful that we were referred to Caylia for our music instruction.
  - name: Julia M, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - I play the piano but when I’m at Caylia’s, it doesn’t matter what level you’re
      on - it just matters that you’re playing the piano and having fun.
  - name: Jerry K, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - It has been great working with you. I felt like you opened the door for me to
      begin playing again. Forever grateful!
  - name: Peter A, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Caylia is a terrific teacher. Caylia is very patient and intuitive and has the
      ability to adjust her teaching style to the different kid’s needs and personalities.
  - name: Cory J, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Caylia has opened my kids up to their own sense of improvisation and confidence.
    - Simply music is helping them to trust their ears and learning to hear music
      differently and therefore play music differently.
    - What’s cool about Caylia is that she takes a song that my kids love and shows
      them, like in 5 minutes, how to play the song. She knows that my kids know the
      songs and chords and in no time at all, they are playing songs that they love.
    - It’s been a fantastic year. My kids have grown as artist, as people with Caylia
      and express themselves and comfortable and that is all we can ask.
  performance:
  - name: Soleil Dakota, San Rafael
    avatar: testimonial-avatar.jpg
    text:
    - I sang out - it was joyous and beautiful. Honestly, I was a little shocked at
      how easy and natural it was . OMG ☺
    - You made the difference. Thank you from the bottom of my heart.
  - name: Eva W, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Thanks for encouraging my daughter and giving her the confidence to sing in
      front of an audience, she has never done that before!
  - name: Tiffany V, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - The performance was a great experience! Thank you so much for working with her
      and giving her so much confidence. You are the best.
  - name: Trigg M, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Wow! Caylia was really magical in bringing my daughter’s inner performer to
      the stage! Caylia found the performer in my daughter! Go Caylia
  idol:
  - name: Eden F, San Rafael
    avatar: testimonial-avatar.jpg
    text:
    - Marin Idol was an extremely fun and interactive way to improve my singing skills.
      It had all the fun of being at a summer  camp with the added bonus of learning
      amazing vocal techniques that I still use to this day. I highly recommend Marin
      Idol for singers of all ages
  - name: Sharon G, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - Marin Idol camp is a joyful, creative and transformative experience. I would
      trust Caylia with anyone who wants to sing from child to adult.
  - name: Ryan B, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - You should sign your kid up for Marin Idol because they’ll meet new friends,
      have a fun time and fun have a fun camp for the summer and also improve their
      singing.
  - name: Suzanne B, Mill Valley
    avatar: testimonial-avatar.jpg
    text:
    - I was nice for me as a parent to know that during the summer, she had this wonderful
      thing to do with her best friend. And with Caylia, in a beautiful setting she
      was also able to polish up some of her skills that she’s learning in her voice
      lessons.
    - One of the things I love about her singing, is that she feels more confident
      using her voice. I find that she is able to express herself better and the singing
      lessons have a lot to do with it.
    - Love Caylia, love Marin Idol, love the lessons and I highly recommend that you
      get your kids started!
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