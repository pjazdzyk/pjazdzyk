<a href="https://energyflowx.com">
  <img src="https://raw.githubusercontent.com/pjazdzyk/energy-flow-x-docu/master/assets/images/efx_reddit_banner.png" alt="EnergyFlowX, Engineering Calculations" width="100%"/>
</a>

## Welcome 🤝

Thanks for stopping by. I'm **Piotr Jażdżyk**, a licensed HVAC engineer and backend software developer. This is where my engineering and software worlds meet: a set of libraries and tools for thermophysics, fluid mechanics, and HVAC, built carefully and from first principles.

**Latest project, [EnergyFlowX](https://energyflowx.com):** a professional web platform for thermophysical property analysis, HVAC process design, and fluid mechanics, powered by the engineering libraries below.

- 🌐 Platform: **[energyflowx.com](https://energyflowx.com)**
- 📚 Documentation: **[energy-flow-x-docu](https://github.com/pjazdzyk/energy-flow-x-docu)**
- ✍️ Articles and write-ups: **[energyflowx.com/articles](https://energyflowx.com/articles)**

## Skills & Technologies

**Backend** · Java · Maven · Spring Boot · Quarkus · JUnit / Mockito · RestAssured · REST API · PostgreSQL · Apache Kafka
**Frontend** · JavaScript · Vue 3 · Quasar · HTML · CSS
**Infrastructure** · Docker · Kubernetes · GitHub Actions
**AI & local inference** · Local LLMs · LM Studio · agentic workflows

<div>
  <img src="https://skillicons.dev/icons?i=java,maven,spring,kafka,postgres,docker,kubernetes,githubactions" alt="backend & infrastructure" />
  <img src="https://skillicons.dev/icons?i=js,vue,html,css,git" alt="frontend" />
</div>

## About Me

I'm a licensed engineer (MSc Eng) with **17+ years in industrial HVAC and MEP design** across power generation, manufacturing, and logistics, and a **backend software developer with 3+ years of commercial experience** building microservices and distributed, Kafka-based messaging systems. I started programming as a hobby long before it became part of my day job, which is probably why I still enjoy it.

I graduated from the **Silesian University of Technology**, Faculty of Environmental Engineering, specialising in HVAC and **computational fluid dynamics (CFD)**. That background, equal parts physics, problem-solving, and project delivery, is what I now bring to software: I designed, built, and maintain the entire EnergyFlowX stack myself, from the equation-of-state engines up through the REST services to the Vue frontend.

I try to be honest about what I know and what I don't. I'd rather ship something correct and well-tested than oversell it.

Lately I've been **deeply interested in AI and local inference**: running open-weight models on my own hardware, experimenting with LM Studio and local LLM tooling, and building agentic workflows. I keep it well away from the calculation path, though. Engineering numbers come from documented equations, not from a model's best guess.

## Engineering Library Ecosystem

EnergyFlowX runs on a purpose-built family of libraries, each designed, written, and tested from scratch. One is fully open source, the rest are private and power the platform from the inside.

<table>
  <tr>
    <th width="168">Library</th>
    <th>Role</th>
    <th width="110">Availability</th>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/pjazdzyk/unitility">Unitility</a></strong></td>
    <td>Physical quantities and units-of-measure framework. Typed <code>Temperature</code>, <code>Pressure</code>, <code>MassFlow</code> and friends, with safe conversion across the whole stack.</td>
    <td><strong>Open source</strong></td>
  </tr>
  <tr>
    <td><strong>numenor-math</strong></td>
    <td>Numerical foundation: robust root-finders (modified Brent-Dekker, Newton-Raphson, multivariate Newton), line search, fixed-point iteration, and sparse linear algebra.</td>
    <td>Private</td>
  </tr>
  <tr>
    <td><strong>flow-symphony</strong></td>
    <td>Universal, domain-generic steady-state hydraulic and pipe-network solver. Solves arbitrary topologies for incompressible and compressible fluids using a Global Gradient Algorithm.</td>
    <td>Private</td>
  </tr>
  <tr>
    <td><strong>hvac-engine-pro</strong></td>
    <td>Psychrometrics and IAPWS thermophysics: humid air, water, steam, ice, and the HVAC process physics behind the platform.</td>
    <td>Private</td>
  </tr>
</table>

My open-source libraries are published to the [Maven Central Repository](https://central.sonatype.com/search?q=synerset) after each release, with quick turnaround on reported issues.

## Connect with Me

<div align="left">
  <a href="https://www.linkedin.com/in/pjazdzyk/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo" />
  </a>
  <a href="https://github.com/sponsors/pjazdzyk" target="_blank">
    <img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" height="40" alt="Sponsor" />
  </a>
</div>
