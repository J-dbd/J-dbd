# Target Image (not rendered in Github)

- This image file has an error issue.

![Typing SVG](../images/title_readme.svg)

# Codes

```html
<link
  href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap"
  rel="stylesheet"
/>

<header>
  <section class="wrapper">
    <div class="terminal">
      <li class="terminal-header">
        <ul class="th-btns">
          <li class="th-btn-close"></li>
          <li class="th-btn-mini"></li>
          <li class="th-btn-max"></li>
        </ul>
      </li>
      <article class="terminal-content">
        <h1>
          <span class="tc-shell">~ J_ManG$</span> Hi! I'm
          <span class="typewriter"></span>
        </h1>
      </article>
    </div>
  </section>
</header>

<style>
  /* ----- Header title CSS ---- */
  .wrapper {
    width: 90%;
    margin: 1rem auto;
    height: 90vh;
  }

  header h1 {
    font-size: 3vmin;
    text-align: left;
    font-family: "Source Code Pro", monospace;
    font-weight: 500;
    margin: 1rem 0 1rem 2rem;

    border-bottom: 0;
  }

  /* --- Header Animation --- */
  @keyframes typing {
    0%,
    21% {
      content: "";
    }
    1%,
    20% {
      content: "J";
    }
    3%,
    19% {
      content: "J-";
    }
    4%,
    17% {
      content: "J-M";
    }
    5%,
    16% {
      content: "J-Ma";
    }
    6%,
    15% {
      content: "J-Man";
    }
    7%,
    14% {
      content: "J-ManG";
    }

    24%,
    51% {
      content: "a ";
    }
    25%,
    50% {
      content: "a d";
    }
    26%,
    49% {
      content: "a de";
    }
    27%,
    48% {
      content: "a dev";
    }
    28%,
    477% {
      content: "a deve";
    }
    29%,
    46% {
      content: "a devel";
    }
    30%,
    45% {
      content: "a develo";
    }
    31%,
    44% {
      content: "a develop";
    }
    32%,
    43% {
      content: "a develope";
    }
    33%,
    42% {
      content: "a developer";
    }

    53%,
    91% {
      content: "a ";
    }
    54%,
    90% {
      content: "a f";
    }
    55%,
    89% {
      content: "a fr";
    }
    56%,
    88% {
      content: "a fro";
    }
    57%,
    87% {
      content: "a fron";
    }
    58%,
    86% {
      content: "a front";
    }
    59%,
    85% {
      content: "a frontE";
    }
    60%,
    84% {
      content: "a frontEn";
    }
    61%,
    83% {
      content: "a frontEnd";
    }
    62%,
    82% {
      content: "a frontEnd-";
    }
    63%,
    81% {
      content: "a frontEnd-e";
    }
    64%,
    80% {
      content: "a frontEnd-en";
    }
    65%,
    79% {
      content: "a frontEnd-eng";
    }
    66%,
    78% {
      content: "a frontEnd-engi";
    }
    67%,
    77% {
      content: "a frontEnd-engin";
    }
    68%,
    76% {
      content: "a frontEnd-engine";
    }
    69%,
    75% {
      content: "a frontEnd-enginee";
    }
    70%,
    74% {
      content: "a frontEnd-engineer";
    }
  }

  .typewriter {
    --caret: currentcolor;
  }

  .typewriter::before {
    content: "";
    animation: typing 13.5s infinite;
  }

  .typewriter::after {
    content: "";
    margin-left: 3px;
    border-right: 3px solid var(--caret);
    animation: blink 0.5s linear infinite;
  }

  @keyframes blink {
    0%,
    100% {
      opacity: 1;
    }
    50% {
      opacity: 0;
    }
  }

  /* --- Header Termial ----*/
  :root {
    --terminal-content-background-color: #323232;
    --terminal-header-background-color: #f6f6f6;
    --terminal-header-border-color: #b8b8b8;
    --terminal-header-button-close: #fc645f;
    --terminal-header-button-minimize: #fdbe41;
    --terminal-header-button-maximize: #35cc4b;
    --terminal-font-size: 1.2;
    --terminal-primary-font-color: #fff;
    --terminal-secondary-font-color: #bfbdbd;
    --max-number-of-typewriter-animation-words: 50;
  }

  .terminal {
    width: 100%;
    height: 100%;
    border-radius: 0.5rem;
    position: relative;
    box-shadow: 0 0.6rem 2rem rgba(#000, 0.6);
  }

  .terminal-header {
    width: calc(100% - 1px);
    height: 1.5rem;
    background-color: var(--terminal-header-background-color);
    border-top-left-radius: 0.3rem;
    border-top-right-radius: 0.3rem;
    border: 0.5px solid var(--terminal-header-border-color);
    border-bottom: 1px solid var(--terminal-header-border-color);

    list-style-type: none;
  }

  .th-btns {
    position: relative;
    height: 100%;
    list-style-type: none;
  }

  .th-btn-close,
  .th-btn-mini,
  .th-btn-max {
    display: block;
    width: 1rem;
    height: 1rem;
    border-radius: 50%;
    display: inline-block;
    position: absolute;
    top: 50%;
    border: 0.1px solid var(--terminal-header-border-color);
  }
  .th-btn-close {
    background-color: var(--terminal-header-button-close);
    background-color: red;
    transform: translate(1rem, -50%);
  }
  .th-btn-mini {
    background-color: var(--terminal-header-button-minimize);
    transform: translate(2.5rem, -50%);
  }
  .th-btn-max {
    background-color: var(--terminal-header-button-maximize);
    transform: translate(4rem, -50%);
  }

  .terminal-content {
    background-color: var(--terminal-content-background-color);
    border-bottom-left-radius: 0.3rem;
    border-bottom-right-radius: 0.3rem;
    overflow: scroll;
  }

  .tc-shell {
    display: inline-block;
    font-weight: bolder;
  }
</style>
```
