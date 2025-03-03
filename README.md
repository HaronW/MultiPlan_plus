# MultiPlan+
Dataset release paper: *EmbodiedAgent: A Scalable Hierarchical Approach to Overcome Practical Challenge in Multi-Robot Control*

![figure](.\figure1.png)

Training dataset: train_MultiPlan+.jsonl (available soon ...)

Test dataset: test_MultiPlan+.jsonl



# Dataset Card

Data structure

- Mission: dict
  - Scenario: str

  - Task: str

- Environment: dict
  - Workspace: list
    - name: str
    - position_on_it: list
  - Robot: list
    - name: str
    - position: str
    - skill: list
    - workload: int
  - Object: list
    - name: str
    - position: str
    - weight: int
  - User: list
    - name: 
    - position
- Planning: list



Visualization: distribution of the length of data samples in MultiPlan+

![figure2](.\figure2.jpg)



# Links

Code: [EmbodiedAgent](https://github.com/HaronW/EmbodiedAgent)

Dataset: [MultiPlan+](https://github.com/HaronW/MultiPlan_plus)

Model weight: [LLaMA-3.1-8B-Multiplan_Plus_NAP](https://huggingface.co/HaronW/LLaMA-3.1-8B-Multiplan_Plus_NAP)



# License

MultiPlan+ is released under the MIT License. See the LICENSE file for more details.