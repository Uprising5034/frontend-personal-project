# Personal Project - Drumbi

## About

### Inspirations

- Yogev Gabay's youtube explainers: [sub-division stuff](https://youtu.be/lDfnhmfD3DU?t=115), [tracks with different bar lengths](https://youtu.be/lDfnhmfD3DU?t=395)
- [Modalic's Beat Scholar](https://www.modalics.com/beatscholar), similar vibes to Yogev's stuff
- [Other drum machines, there's tonnes of them](https://www.ordrumbox.com/)
- [A tale of two clocks](https://web.dev/articles/audio-scheduling) and [metronome app](https://cwilso.github.io/metronome/), both by Chris Wilson

### Tech Stack

- JavaScript / React
- TailWindCSS

### Why Stack

- React is what I'm practised in
- The instructions said not to use TypeScript 😭
- I like using TailWind

### What I enjoyed

- TODO:

### What I found challenging / surprising

- From prototyping:
  - How many audio contexts to use, I initially only used one global context but could not envision how to loop the playtrack as well as add more stuff during playback

- From the ~~real thing~~ second prototype:
  - I was surprised I haven't used `useRef()` before this point, but it's benefits were apparent doing this project. Timing is key for music applications, so one doesn't want render timing to get in the way of specific things. It was also amusing to see the [example on the React docs, using `setInterval()`,](https://react.dev/reference/react/useRef#referencing-a-value-with-a-ref) was one of the exact use cases I was after.
  - Changing bpm (with the way I'm leaving it!), changing the bpm without affecting the current rhythm proved a lot more tricky than I envisioned. I thought I would be able to create a new `setInterval` instance within the currently running one but to no avail. Research took me to this [metronome app](https://cwilso.github.io/metronome/) and it's accompanying article. Now listed in the inspirations.

## Links

- TODO: Deployed
- [Github Repo](https://github.com/Uprising5034/drumbi)
