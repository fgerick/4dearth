---
title: "People involved in the project"
layout: "simple"
date: 2025-09-26
---

<style>
	/* People list layout (works on light/dark; uses fallbacks if theme vars differ) */
.people-list {
  display: grid;
  gap: 1rem;
}


.people-card { display: grid; grid-template-columns: auto 1fr; gap: 1rem; align-items: start; }

.people-avatar {
  width: 96px;
  aspect-ratio: 1 / 1;
  border-radius: 50%;
  border: 1.5px solid;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  flex: 0 0 auto;
}


.people-body { min-width: 0; }

.people-name {
  font-weight: 700;
  font-size: 1.15rem;
  line-height: 1.2;
  margin: 0;
}

.people-affiliation {
  margin-top: 0.15rem;
  font-size: 0.85rem;
  color: var(--color-text-weak); /* Congo var with fallback */
}

.people-summary {
  margin-top: 0.5rem;
}

/* Slightly larger on wider screens */
@media (min-width: 768px) {
  .people-avatar {
    width: 100px;
    height: 100px;
  }
  .people-name {
    font-size: 1.2rem;
  }
}

</style>



## Researchers


{{< person
    name="Dr Julien Aubert"
    affiliation="Institut de Physique du Globe de Paris"
    img="img/people/jaubert.jpg"
>}}
I am a CNRS researcher walking along the path. Read about my journey on [my website](https://www.ipgp.fr/~aubert/). Lorem ipsum dolor sit amet, consectetur adipiscing elit. In volutpat vehicula sodales. Cras tempor molestie libero, eu iaculis dolor vehicula at. Ut est mi, maximus quis vulputate quis, imperdiet eu libero. Proin tincidunt molestie ligula sed tempus. Donec dignissim eget eros non vestibulum. Maecenas interdum ligula at est consectetur vulputate a a dolor. Aenean sit amet gravida mi. Quisque sem massa, sodales non elit ut, faucibus suscipit metus. 
{{< /person >}}


{{< person
    name="Dr Felix Gerick"
    affiliation="University of Leeds"
    img="img/people/gerick.jpg"
>}}
I am a postdoctoral fellow, working on waves in the core. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In volutpat vehicula sodales. Cras tempor molestie libero, eu iaculis dolor vehicula at. Ut est mi, maximus quis vulputate quis, imperdiet eu libero. Proin tincidunt molestie ligula sed tempus. Donec dignissim eget eros non vestibulum. Maecenas interdum ligula at est consectetur vulputate a a dolor. Aenean sit amet gravida mi. Quisque sem massa, sodales non elit ut, faucibus suscipit metus. 
{{< /person >}}
