<!-- This readme was built off of this template: https://github.com/othneildrew/Best-README-Template/tree/master -->
<a name="readme-top"></a>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables  
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Version][version-shield]][version-url]
[![Contributors][contributors-shield]][contributors-url]
[![License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/VerdanTech">
    <img src="https://github.com/VerdanTech/.github/blob/main/profile/graphics/logo.png" alt="Logo" width="200" height="200">
  </a>

<h3 align="center">VerdanTech</h3>

  <p align="center">
    A garden productivity tool, agro-ecology model, and IoT platform
    for a sustainable and cooperative future.
    <br />
    <a href=""><strong>Try it yourself »</strong></a>
    <br />
    <br />
    <a href="https://discord.gg/U8ps6YCc">Discord</a>
    ·
    <a href="https://youtu.be/jGFHhRVdxRM">YouTube</a>
    ·
    <a href="">Donate</a>
    <br />
  </p>
</div>

VerdanTech is an open source software and embedded systems project best summarized as a fusion between:

- **Garden Productivity Engine**: An intricate and interactive model of agriculture which facilitates the data-driven planning of productive spaces and the collaborative coordination of labour at any scale.
- **Agro-Ecology Optimization Model**: A model which captures the relationship between agriculture and the broader ecological system, with the goal of producing a healthy abundance and diversity of food with minimal reliance on conditions of resource depletion and ecological destruction.
- **IoT Automation Suite**: An Internet-of-Things (IoT) platform which serves as an extensible interface for integration with external APIs and a set of embedded devices designed to automate the process of obtaining measurements and executing tasks.

In short, the goal of VerdanTech is to provide tools that make it easier to collaboratively plan, track, optimize, and automate agro-ecological systems at any scale.

VerdanTech has been in development since late 2022, or early 2021 if we count the [initial attempt](https://www.youtube.com/watch?v=w0TwPI7bLp8&ab_channel=TotalVeganicFuturism) at a similar idea. VerdanTech is built with [sentientist values](https://sentientism.info/) in mind, and as such does not consider sentient beings as acceptable subjects of exploitation for food or any other purpose.

<!--- See the video introduction to VerdanTech here: --->
<!--- [![Watch the video](https://img.youtube.com/vi/jGFHhRVdxRM/maxresdefault.jpg)](https://youtu.be/jGFHhRVdxRM) --->

<div>
<!-- TABLE OF CONTENTS -->
<details>
    <summary>Table of Contents</summary>
    <ul>
        <li>
            <a href="#background">Background</a>
            <ul>
                <li>
                    <a href="#agriculture">Agriculture</a>
                </li>
                <li>
                    <a href="#ecology">Ecology</a>
                </li>
                <li>
                    <a href="#modern-industrial-agriculture-and-the-ecological-alternative">Modern Industrial Agriculture and the Ecological Alternative</a>
                </li>
                <li>
                    <a href="#the-goals-and-values-of-verdantech">The Goals and Values of VerdanTech</a>
                </li>
            </ul>
        </li>
        <li>
            <a href="#codebase">Codebase</a>
        </li>
        <li>
            <a href="#features">Features</a>
        </li>
    </ul>
</details>
<br />
</div>

# Background

*This section highlights the problems that VerdanTech aims to solve and the nature of the solutions.*

## Agriculture

Dictionary.com [defines agriculture as](https://www.dictionary.com/browse/agriculture):
> the science, art, or occupation concerned with cultivating land, raising crops, and feeding, breeding, and raising livestock; farming.

VerdanTech is built with [sentientist values](https://sentientism.info/) in mind, and as such does not consider sentient beings as acceptable subjects of exploitation for food or any other purpose. As a result, the word agriculture in the context of any VerdanTech documentation uses this definition:
> the science, art, or occupation concerned with cultivating land and raising crops; farming.

The specific term "animal agriculture" retains its meaning. 

<p align="right"><a href="#readme-top">back to top</a></p>

## Ecology

Merriam Webster [defines ecology as](https://www.merriam-webster.com/dictionary/ecology)
> a branch of science concerned with the interrelationship of organisms and their environments, the totality or pattern of relations between organisms and their environment.

In our world today, the relationship between ecology and human society is more important than ever. We rely on Earth's ecosystems for services that are vital to our existence. The Millenium Ecosystem Assessment provides [four categories](https://earth.org/what-are-ecosystem-services/) of ecosystem services:

- **Provisioning services** produce material resources such as food, water, fibers, oil, and minerals. 
- **Regulating services** maintain favorable ecological, climate, and other conditions, such as climate regulation, flood protection, pollination, and water purification. 
- **Supporting services** maintain the foundation of a functioning ecosytem, including the water cycle, nutrient cycle, and biodiversity.  
- **Cultural services** provide non-material benefits such as spiritual, intellectual, recreational, and aesthetic values.

Despite our reliance on these services, we maintain relationships with the ecologies responsible for them that are largely unsustainable. Keeping in mind the broad and varied scope of ecosystem services, a society cannot be sustained when its consumption of resources or emissions of waste exceed the regenerative or absorbative capacities of its environment. A society of these conditions undermines not only its own wellbeing but also that of fellow inhabitants and the health of the ecosystem itself. 

Our environment is planet Earth, and the combined ecological impact of all our systems of extraction, production, pollution, and emission amounts to a truly devastating level of resource depletion, biosphere destruction, climate change, and more. The situation is intolerable. It falls on us to figure out how we need to adapt and then to undertake it.

A truly sustainable society requires many adaptations. Some are technological, including changes to what resources we depend on and what procceses we use to achieve our goals. Technological adaptations involve some combination of meeting our energy and material demands through sustainable resources and finding ways to reduce the amount of those resources required for the services we demand. Other adaptations are social, including changes to what our goals are and thus what services we demand and how we organize ourselves to meet them. Social adaptations involve the creation of human organization centered around solidarity, equality, and cooperation towards collective success and the equal interest of all individuals across species and generations.

Almost all of these adaptations are interconnected, and massive in scope. VerdanTech focuses specifically on agriculture and its relation to ecology and the organization of human labour.

<p align="right"><a href="#readme-top">back to top</a></p>

## Modern Industrial Agriculture and the Ecological Alternative

Our modern industrial agriculture system leaves much to be desired in the way of ecological sustainability. To summarize this article titled [How sustainable agriculture can address the environmental and human health harms of industrial agriculture](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1240832/):
- The intensive use of monocultures, synthetic fertilizers, and pesticides causes biodiversity destruction and environmental pollution.
- A reliance on non-renewable fossil fuels for the production of chemical inputs and mechanical work, as well as the use of renewable resources such as soil and water faster than their rate of regeneration, creates a dependency on unsustainable conditions of ecological destruction. 
- The monopolization of the means of agricultural production leads to a social rift between producers and consumers. 

In a sentence, the modern industrial agriculture system is dependent on systems which undermine the conditions required for its own existence and that of society. 
 
The application of ecological analysis to agriculture highlights a clear need for a transition to sustainable agriculture as a core sector of sustainable development. The concept of agro-ecology seeks to provide a framework for understanding the path that we need to take. The United Nations Food and Agriculture Organization (FAO) [defines agro-ecology as](https://www.fao.org/3/i9037en/i9037en.pdf):
>Agroecology is an integrated approach that simultaneously applies ecological and social concepts and principles to the design and management of food and agricultural systems. It seeks to optimize the interactions between plants, animals, humans and the environment while taking into consideration the social aspects that need to be addressed for a sustainable and fair food system. Rather than tweaking the practices of unsustainable agricultural systems, agroecology seeks to transform food and agricultural systems, addressing the root causes of problems in an integrated way and providing holistic and long-term solutions. [Agroecology] is based on bottom-up and territorial processes, helping to deliver contextualised solutions to local problems. Agroecological innovations are based on the co-creation of knowledge, combining science with the traditional, practical and local knowledge of producers. By enhancing their autonomy and adaptive capacity, agroecology empowers producers and communities as key agents of change.

A truly sustainable transformation of our agriculture system faces great challenges. Possibly the greatest challenge is articulated by an article titled [Transitioning to Sustainable Agriculture Requires Growing and Sustaining an Ecologically Skilled Workforce](https://www.frontiersin.org/articles/10.3389/fsufs.2019.00096/full):
>The single greatest sustainability challenge for agriculture may well be that of replacing non-renewable resources with agroecologically skilled people.

In other words, the transition away from simple artifical ecosystems and non-renewable inputs to diverse ecologies integrated with renewable cycles requires more human labour managing more complex systems.

<p align="right"><a href="#readme-top">back to top</a></p>

## The Goals and Values of VerdanTech

In short, the goal of VerdanTech is to create tools which:
- Minimize the knowledge and cognitive load required to plan, track, optimize, and automate agro-ecological systems at any scale.
- Transfer the co-creation of ecological knowledge into digital models made freely accessible to contextualized application.
- Facilitate the horizontal organization of human labour through collaborative systems.
- Ultimately enhance our adaptive capacity towards a sustainable agriculture system by putting the means of agro-ecological production and innovation into the hands of everyone.

The ideal solution that VerdanTech represents can be thought of as an abstract model which takes in as input all available data regarding the conditions of a local biosphere and produces as output a comprehensive list of steps required to transition that biosphere into the optimal agro-ecological system.

The project as a whole encompasses three main areas:

- **Garden Productivity Engine**: At its core, VerdanTech is a garden productivity tool which can be used by growers to assist in planning and tracking their systems, whether that is a single container, a sizeable backyard garden, or a sprawling food forest. This includes features such as the visualization of planting calendars, the manual and automatic spatio-temporal planning of crops, the distillation of available data into a realizable set of actions, and the synchronous multi-client use of all these systems. While the facilitation of a sustainable agriculture revolution is aspirational, these core features are intended to be useful to, if nothing else, the hobbyist gardener.
- **Agro-Ecology Optimization Model**: The productivity model is extended to encompass metrics relevant to the sustainability of agriculture systems, including biodiversity, habitat, climate, nutrient and water cycles, and more. These metrics can then be used to shift productivity towards a holistic model of ecological health, allowing for the optimization of these systems to produce the desired quantity and diversity of food within a framework of ecological integration. 
- **IoT Automation Suite**: The model required to achieve these goals becomes more effective the easier it is to supply data as input and execute outputs in the world. Thus, the goal is to follow an internet-of-things approach to connecting the model with external devices and automating the process of obtaining input data and executing output tasks. Input devices include weather services, temperature, moisture, and rainfall sensors, and images paired with computer vision. Output devices include irrigation controllers and robotic farming equipment. The sci-fi endgame of this concept is to support an end-to-end fully autonomous agriculture system.

<p align="right"><a href="#readme-top">back to top</a></p>

# Codebase

The project currently is made up of several repositories:
- [Outline](https://github.com/VerdanTech/VerdanTech-Outline) contains high level conceptual overviews and design documents, including summaries and maps of the domain model and wireframes for the web application.
- [Backend](https://github.com/VerdanTech/VerdanTech-Backend) contains a Python HTTP API that serves as a backend for the VerdanTech web application.
- [Frontend](https://github.com/VerdanTech/VerdanTech-Frontend) contains a Svelte-Kit static adapter application which serves as a frontend for the web application. 
- [Deployment](https://github.com/VerdanTech/VerdanTech-Deployment) contains web application deployment orchestration. 
- [Drip](https://github.com/VerdanTech/VerdanTech-Drip) contains an embedded IOT irrigation controller.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

# Features

VerdanTech is currently still in a pre-alpha state. As there is only one contributor, these things take a while.

1.0 (Minimum Viable Product) Goals:
- User registration, authentication, and management system. (Backend 75%, frontend 40%)
- Gardens which act as containers for most application data and workspaces shared by multiple Users. (Backend 40%, frontend 5%)
- Workspaces which give spatial context to geometries such as Plants and PlantingAreas. (Backend 5%, frontend 0%)
- Attribute system which flexibly represents a diverse range of environmental and biological characteristics. (Backend 15%, frontend 0%)
- Cultivars which are compositions of attributes into representations of plant types, species, and varieties. (Backend 5%, frontend 0%)
- Plants which are representations of physical instances of plants and their lifecycles and behaviours within PlantingAreas. (Backend 5%, frontend 0%)
- Agroplans which are integrations of past/current and future instances of Plants into plans which are validated against physical contstraints and can be optimized. (Backend 0%, frontend 0%)
- A Planner interface which visualizes the planting windows of plant varieties over time and the 2D representation of workspaces throughout time. (Backend 0%, frontend 0%)

Future goals:
- AgroplanGenerators which which create and transform Agroplans according to objectives (ex. quantities and proportions of plant varieties, maximum calories, biodiversity) using algorithmic strategies (ex. simulated annealing).
- Actions which are to-do lists intelligently generated from garden state.
- Environmental Inputs (ex. Temperature, Rainfall, Images), and Outputs (ex. Irrigation Control) which add behavior to the model, as well as Devices (ex. APIs, embedded systems) which expose these ports to other systems.
- Differential synchronization of client and server data for smooth multi-client use. 

[version-shield]: https://img.shields.io/badge/version-0.0.1-blue?style=for-the-badge
[version-url]: https://github.com/nathanielarking/Autonomous-Agriculture/releases
[contributors-shield]: https://img.shields.io/github/contributors/nathanielarking/VerdanTech.svg?style=for-the-badge
[contributors-url]: https://github.com/nathanielarking/VerdanTech/graphs/contributors
[license-shield]: https://img.shields.io/github/license/nathanielarking/VerdanTech.svg?style=for-the-badge
[license-url]: https://github.com/nathanielarking/VerdanTech/LICENSE.txt