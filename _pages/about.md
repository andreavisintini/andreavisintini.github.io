---
permalink: /
title: "About me"
author_profile: true

---
I am a PhD Candidate at Scuola Normale Superiore di Pisa. My PhD is part of the HuME PhD, joint with IUSS Pavia and University of Milan.  

My PhD Supervisor is Mario Piazza. My PhD Co-Supervisor is Achille Varzi.

I was a visiting scholar in New York City during the Spring Semester 2025, at CUNY Graduate Center, under the supervision of Graham Priest.

I work primarily in metaphysics and philosophical logic.

Specifically, my research focuses on modality and persistence. I have written a PhD thesis on Actualist Five-dimensionalism: a theory that combines the view the only the actual world exists with the view that ordinary objects are five-dimensional entities extended across possible worlds.

I am a football fan (I unfortunately support Udinese), and also a Formula1 fan (I unfortunately support Ferrari).

I have an orange cat named <span class="macbeth-reveal"><button class="macbeth-trigger" type="button" aria-expanded="false">Macbeth</button><img class="macbeth-image" src="/images/Macbeth.JPG" alt="Macbeth" /></span>.

<style>
  .macbeth-reveal {
    display: inline-block;
    position: relative;
    vertical-align: baseline;
  }

  .macbeth-trigger {
    border: none;
    background: transparent;
    padding: 0;
    margin: 0;
    font: inherit;
    font-weight: 600;
    color: #2a7ae2;
    cursor: pointer;
    transition: color 0.2s ease;
  }

  .macbeth-trigger:hover,
  .macbeth-trigger:focus-visible {
    color: #1d5fbf;
    text-decoration: underline;
    outline: none;
  }

  .macbeth-image {
    display: none;
    width: min(320px, 70vw);
    margin-top: 0.7rem;
    border-radius: 14px;
    box-shadow: 0 12px 28px rgba(0, 0, 0, 0.16);
    border: 1px solid rgba(0, 0, 0, 0.09);
    background: white;
  }

  .macbeth-reveal.is-open .macbeth-image {
    display: block;
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const triggers = document.querySelectorAll('.macbeth-trigger');

    triggers.forEach(function (trigger) {
      const reveal = trigger.closest('.macbeth-reveal');
      if (!reveal) return;

      trigger.addEventListener('click', function () {
        const isOpen = reveal.classList.toggle('is-open');
        trigger.setAttribute('aria-expanded', String(isOpen));
      });
    });
  });
</script>
