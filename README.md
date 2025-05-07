Build a Bioinformatics Solubility Dashboard in Snowflake
In this notebook, you'll build a bioinformatics project from scratch in Snowflake.

Briefly, we're using the Delaney solubility data set. Solubility is an important property for successful drug discovery efforts and is amongst one of the key metrics used in defining drug-like molecules according to the Lipinski Rule of 5.

In a nutshell, here's what you're building:

Load data into Snowflake
Perform data preparation using Pandas
Build a simple dashboard with Streamlit
About molecular solubility
Molecular solubility is a crucial property in drug development that affects whether a drug can reach its target in the human body. Let me explain why it matters in simple terms.

Solubility
Solubility is a molecule's ability to dissolve in a liquid, which literally means the ability to dissolve in human bloodstream and transport to its desired target in the human body. If it can dissolve, it can't work!

Poorly soluble drugs might require higher doses or special formulations, leading to potential side effects or complicated treatment regimens. So we want drugs that are both effective and yet soluble so that fewer of it is required so as to minimize potential side effects.

Lipinski's Rule of 5
Drug development often refer to a guidelines known as the Lipinski's Rule of 5 to predict whether a molecule will be soluble enough to make a good oral drug. This includes factors like:

Molecule's size
How water-loving or water-repelling it is
Number of hydrogen bond donors and acceptors
Understanding and optimizing solubility helps pharmaceutical companies develop effective medicines that can be easily administered and work efficiently in the body.

References
ESOL:  Estimating Aqueous Solubility Directly from Molecular Structure - https://pubs.acs.org/doi/10.1021/ci034243x
st.bar_chart - https://docs.streamlit.io/develop/api-reference/charts/st.bar_chart
st.expander - https://docs.streamlit.io/develop/api-reference/layout/st.expander
st.slider - https://docs.streamlit.io/develop/api-reference/widgets/st.slider
