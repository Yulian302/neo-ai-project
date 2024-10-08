# **NeoAi: Open-Source Machine Learning Platform**

NeoAi is an open-source web application designed to empower users in the realm of machine learning. The platform provides a seamless experience for leveraging built-in machine learning models, storing and managing personal models, and tailoring them to individual needs. Still in active development, NeoAi is committed to provide access to machine learning capabilities and fostering a collaborative community of developers, researchers, and enthusiasts.

![NeoAi Platform Preview](./NeoAiPreview.png)

<!-- > [!IMPORTANT]
> This project is still under development. Any contributions are welcomed! -->

## Links
- [**NeoAi: Open-Source Machine Learning Platform**](#neoai-open-source-machine-learning-platform)
  - [Links](#links)
  - [Features](#features)
  - [Diagrams](#diagrams)
    - [Data layer (MySQL)](#data-layer-mysql)
    - [Business processes design (context diagram)](#business-processes-design-context-diagram)
    - [UI/UX workflow diagram](#uiux-workflow-diagram)
    - [Proposed deployment diagram](#proposed-deployment-diagram)
  - [Contribution](#contribution)
  - [License](#license)



## Features
- Built-in Models: Access a variety of pre-trained machine learning models to jumpstart your projects.

- Model Storage: Seamlessly store and organize your own machine learning models directly on the platform. **(to implement)**

- Customization: Tailor and fine-tune models to suit your specific requirements, fostering a personalized and adaptive approach to machine learning. **(to implement)**

- User-Friendly Interface: Enjoy a user-friendly web application interface that simplifies complex machine learning tasks and workflows.

## Diagrams

### Data layer (MySQL)
<br/>
<div  style="text-align: center;">
<span style="font-weight: bold;">Logic layer</span>
</div>

![Logic layer](./images/data/logic_layer.png)

<br/>

<div  style="text-align: center;">
<span style="font-weight: bold;">Physical layer</span>
</div>

![Physical layer](./images/data/physical_layer.png)

### Business processes design (context diagram)
<section style="display: flex; flex-direction: column; gap: 30px;">

<div>

![Context diagram level 0](./images/bp/context_l0.png)
<div style="text-align: center;">
<span style="font-weight: bold;">Context diagram (level 0)</span>
</div>
</div>

<div>

![Context diagram level 1](./images/bp/context_l1.png)
<div style="text-align: center;">
<span style="font-weight: bold;">Context diagram (level 1)</span>
</div>
</div>

<div>

![Context diagram level 2.1](./images/bp/context_l2.1.png)
<div style="text-align: center;">
<span style="font-weight: bold;">Context diagram (level 2.1)</span>
</div>
</div>

<div>

![Context diagram level 2.2](./images/bp/context_l2.2.png)
<div style="text-align: center;">
<span style="font-weight: bold;">Context diagram (level 2.2)</span>
</div>
</div>

<div>

![Context diagram level 2.3](./images/bp/context_l2.3.png)
<div style="text-align: center;">
<span style="font-weight: bold;">Context diagram (level 2.3)</span>
</div>
</div>

</section>

### UI/UX workflow diagram

<br/>

![UI/UX workflow diagram](./images/uiux/workflow.png)

### Proposed deployment diagram

<br/>

<div style="display: flex; flex-direction: column; gap: 10px;">
<div style="text-align: center;">
<span style="font-weight: bold;">System deployment using AWS</span>


![System nodes deployment diagram](./images/deployment/system.png)
</div>

<div style="text-align: center;">
<span style="font-weight: bold;">Backend deployment using AWS</span>


![Backend deployment diagram](./images/deployment/backend.png)
</div>

</div>

## Contribution

How to Contribute:
1) Fork the Repository: Start contributing by forking the NeoAi repository.

2) Clone Locally: Clone the forked repository to your local machine.

3) Hack Away: Contribute to NeoAi by fixing bugs, adding new features, or improving existing ones.

4) Submit Pull Requests: Share your contributions by submitting pull requests. Collaborative efforts to enhance the platform are welcomed.

Let's try to shape the future of machine learning together with NeoAi!


## License
Distributed under the MIT License. See LICENSE for more information.