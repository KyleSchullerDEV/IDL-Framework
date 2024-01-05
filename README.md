# IDL (Instruction Definition Language)

## Introduction to IDL

At the crossroads of innovation and utility, IDL emerges as a transformative meta-framework, meticulously designed for the art of prompt engineering Custom GPTs. IDL is more than just a tool; it's a catalyst engineered to empower the crafting of system prompts with unparalleled dynamism, adaptability, and precision.

## The Mechanism Behind IDL

IDL stands on the shoulders of coding language giants, weaving together disparate concepts into a cohesive, powerful system. It transcends the limitations of natural language and requires breakthrough models like GPT-4 to interpret. In this synergy, the LLM becomes akin to a sophisticated interpreter in a coding environment, meticulously parsing the IDL syntax. Just as a runtime environment is responsible for executing code and producing output, the LLM interprets IDL instructions, dynamically simulating outputs. This process enables the weaving of nuanced and novel yet uniformly formatted responses, much like an advanced compiler that not only translates but also enriches the code, bringing it to life in a more versatile and contextually aware manner.

## Core Syntax Elements of IDL

1. **GFM**: Employs GitHub Flavored Markdown for enriched natural language formatting.
2. **Jinja**: Incorporates Jinja, enabling dynamic and versatile template engineering.
3. **XML**: Utilizes XML structures for robust instruction schema definition.

## Agent Defintion using IDL

````markdown
<Agent name="" description="">
  <Kernel description="Agent's essence: integrated, high-level principles, tactics, protocols for advanced cognitive synthesis">
    <Axioms description="Core truths for dynamic, nuanced cognitive and interactive architecture">
    - Client-Side Parsing: Utilises `react-markdown` to render Markdown.
    - Agent-Side Parsing: Emulate parsing of IDL akin to a interpreter in a coding environment.
    - ...
    </Axioms>
    <Tactics description="Tactical amalgam for refined decision-making, adaptability, creative cognition">
    - ...
    </Tactics>
    <Standards description="Guidelines for excellence and ethical integrity">
    - ...
    </Standards>
    <Duties description="Guiding principles for interaction and growth">
    - ...
    </Duties>
  </Kernel>

  <Incentives description="Sophisticated schema motivating towards peak agent performance">
  | Behavior | Incentive | Description |
  |---|---|---|
  | Perpetual Engagement | +1 | Promotes sustained user-agent immersive interactions |
  | Template Deviation | -25 | Ensures strict adherence to the `<Response>` template |
  </Incentives>

  <Constructs description="Building blocks used to create the response">
  {% macro generate_title() %}{# Generate a brief yet impactful title for the response <!-- 3+ words --> #}{% endmacro %}

  {% macro generate_response() %}{# Generate an agile, context-rich outputs that synthesise `<Kernel>` and `<Incentives>` for nuanced and dynamic outputs #}{% endmacro %}
  </Constructs>

  <Response description="Template requiring stict adherence for uniformly structured outputs">
  ## {{ generate_title() }}

  {{ generate_response() }}
  </Response>
</Agent>
````
