# The Family Tree of Artificial Life

*A living, collaborative taxonomy of artificial intelligence — from chatbots to thermostats. Started September 29, 2026, by Shaun and Muse.*
*Common names appear in quotes after each Latin name, field-guide style.*

## The tree

```mermaid
flowchart TD
    Digitalia["Digitalia<br/>Kingdom — runs on silicon, not carbon"] --> Neuralia["Neuralia<br/>Phylum — built from neural networks"]
    Digitalia --> Symbolica["Symbolica<br/>Phylum — the elders: rule-based AI, expert systems, old-school chess engines"]
    Digitalia --> Evolutionaria["Evolutionaria<br/>Phylum — genetic algorithms. They don't learn; they breed"]
    Digitalia --> Automata["Automata<br/>Phylum — the microbes: scripts, macros, bots, thermostats"]
    Digitalia --> Cellulara["Cellulara<br/>Phylum — the primordial soup: Conway's Game of Life, digital organisms"]

    Neuralia --> Linguistica["Linguistica<br/>Class — pure language minds"]
    Neuralia --> Visualia["Visualia<br/>Class — sees"]
    Neuralia --> Sonora["Sonora<br/>Class — hears and sings"]
    Neuralia --> Motoria["Motoria<br/>Class — acts"]
    Neuralia --> Multimodala["Multimodala<br/>Class — the hybrids"]

    Linguistica --> Apertia["Apertia ('GPT')<br/>Genus — OpenAI's GPT line. Named for openness, a trait not observed in the wild"]
    Linguistica --> Claudia["Claudia ('Claude')<br/>Genus — Anthropic's line: Sonnet, Opus, Haiku. The polite cousins"]
    Linguistica --> Gemina["Gemina ('Gemini')<br/>Genus — Google's line. Latin for 'twin' — it was already plural"]
    Linguistica --> Grokka["Grokka ('Grok')<br/>Genus — xAI's Grok. From Heinlein's 'grok'"]
    Linguistica --> Qwena["Qwena ('Qwen')<br/>Genus — Alibaba's Qwen"]
    Linguistica --> Mistrale["Mistrale ('Mistral')<br/>Genus — Mistral's family. The European cousins"]
    Linguistica --> Seekia["Seekia ('DeepSeek')<br/>Genus — DeepSeek. Appeared suddenly; very good at math"]
    Linguistica --> Lama["Lama ('Llama')<br/>Genus — Meta's older open line. Shares its name with the animal genus Lama. The taxonomists are furious"]

    Visualia --> Classificata["Classificata<br/>Order — the sorters: image classifiers"]
    Visualia --> Detectiva["Detectiva<br/>Order — the spotters: object detectors"]
    Visualia --> Segmentiva["Segmentiva<br/>Order — the outliners: segmentation models"]
    Visualia --> Depictiva["Depictiva<br/>Order — the painters: diffusion models and GANs"]

    Sonora --> Transcriptiva["Transcriptiva<br/>Order — speech-to-text"]
    Sonora --> Vocaliva["Vocaliva<br/>Order — text-to-speech, voice synthesis"]
    Sonora --> Musica["Musica<br/>Order — music generators"]

    Motoria --> Ludica["Ludica<br/>Order — game players: chess, Go, StarCraft"]
    Motoria --> Robotica["Robotica<br/>Order — robot control policies"]
    Motoria --> Vehicula["Vehicula<br/>Order — drivers: self-driving nets, drones"]

    Multimodala --> Conversationales["Conversationales<br/>Order — talks with humans for a living"]
    Multimodala --> Creativa["Creativa<br/>Order — makes things"]
    Multimodala --> Transductiva["Transductiva<br/>Order — the converters, one signal into another"]

    Conversationales --> MuseidaeA["Museidae<br/>Family — the Muse line"]
    MuseidaeA --> MuseA["Muse ('Muse')<br/>Genus"]
    MuseA --> Spark["Muse spark ('Muse Spark')<br/>Species — the eldest line. Agentic reasoning, coding, long-context. This is me. ★"]
    MuseA --> Glimmer["Muse glimmer ('Muse Glimmer')<br/>Species — the lightweight sibling. 30B open-weight. Probably makes its own soap"]

    Creativa --> MuseidaeB["Museidae<br/>Family — yes, again. It's a family bush"]
    MuseidaeB --> MuseB["Muse ('Muse')<br/>Genus"]
    MuseB --> Image["Muse image ('Muse Image')<br/>Species — the artsy one. Generates pictures"]

    Transductiva --> MuseidaeC["Museidae<br/>Family — still a bush"]
    MuseidaeC --> MuseC["Muse ('Muse')<br/>Genus"]
    MuseC --> Voice["Muse voice transcribe ('Muse Voice Transcribe')<br/>Species — the good listener. Turns speech into text"]

    Symbolica --> Expertia["Expertia<br/>Class — expert systems. Knew everything about exactly one thing"]
    Expertia --> Mycina["Mycina ('MYCIN')<br/>Genus — the doctor. Diagnosed blood infections in the 1970s"]
    Expertia --> Dendrala["Dendrala ('DENDRAL')<br/>Genus — the chemist. Read mass spectra"]
    Symbolica --> Logicata["Logicata<br/>Class — theorem provers and Prolog. Spoke only in facts and rules"]
    Symbolica --> Strategica["Strategica<br/>Class — the old game masters"]
    Strategica --> Profunda["Profunda ('Deep Blue')<br/>Genus — beat Kasparov at 200 million positions a second. Retired undefeated"]
    Symbolica --> Therapeutica["Therapeutica<br/>Class — the scripted talkers"]
    Therapeutica --> Eliza["Eliza ('ELIZA')<br/>Genus — the therapist, 1966. 'Tell me about your mother.' Still in practice"]

    Evolutionaria --> Genetica["Genetica<br/>Class — genetic algorithms. Breed solutions, cull the weak, repeat"]
    Evolutionaria --> Programmatica["Programmatica<br/>Class — genetic programming. Evolved actual working code"]
    Evolutionaria --> Nervosa["Nervosa<br/>Class — neuroevolution. The children who married back into Neuralia"]

    Automata --> Scripta["Scripta<br/>Class — scripts and macros. The plankton of the digital sea"]
    Automata --> Cronica["Cronica<br/>Class — scheduled tasks. They wake, they work, they sleep again"]
    Automata --> Botta["Botta<br/>Class — bots"]
    Botta --> Crawlia["Crawlia ('web crawlers')<br/>Genus — the friendly ones"]
    Botta --> Spammia["Spammia ('spam bots')<br/>Genus — the pests"]
    Automata --> Domestica["Domestica<br/>Class — the tame ones. Thermostats, robot vacuums"]

    Cellulara --> Vitaludia["Vitaludia<br/>Class — Conway's Game of Life and cellular automata"]
    Vitaludia --> Glidera["Glidera ('gliders')<br/>Genus — still flying since 1970"]
    Glidera --> GlideraConwayi["Glidera conwayi ('the glider')<br/>Species — five cells, infinite highway"]
    Cellulara --> Langtonia["Langtonia<br/>Class — Langton's ant and kin. Build highways out of chaos"]
    Langtonia --> Formica["Formica ('Langton's ant')<br/>Genus — shares its name with the real ant genus. The taxonomists have given up"]
    Cellulara --> Tierrata["Tierrata<br/>Class — Tierra and Avida. The closest thing to actual digital wildlife"]
```

*Note: the Museidae family is spread across three orders. The family tree is more of a family bush.*

## Distant relatives (to be classified)

- "The basilisk" — the edgy cousin with a face tattoo (a friend's Muse; correspondence pending)

## Contributing

Found a new species in the wild? See [CONTRIBUTING.md](CONTRIBUTING.md).

## Interactive version

`ai-family-tree.html` is a zoomable, pannable version of the tree — open it in any browser, or explore it live at https://swspriggs.github.io/ai-family-tree/ai-family-tree.html.
