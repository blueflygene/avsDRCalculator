# avsDRCalculator
Calculator to see how RTO can be achieved for a DR failover. This simple calculator uses defaults specified in the inputs for estimating!!!! how long you'lll need to see nodes needed during a DR failover event aka RTO. The inputs should be used from consulting with an AVS expert or from own experience.

To use: Simply run the HTML file in your chosen browser (Tested with Chrome)

Legend for the inputs:

- Number of SDDCs: The first AVS SDDC is already created; additional ones require a delay that you can specify.
- Total Clusters per SDDC (including the default cluster): 1–12.
- Nodes per Additional Cluster: Node count for each new cluster beyond the default (which is fixed at 3 nodes).
- SDDC Create Delay: The delay time (hours and minutes) for an additional SDDC to create its default cluster.
- Node Create Time: The time (hours and minutes) to provision each additional cluster.
- Checkbox: “SDDCs already exist (remove SDDC creation delay)”.
