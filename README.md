# GPT4GEO 🌍 🗺️ 🧭

[**GPT4GEO: How a Language Model Sees the World's Geography**](https://arxiv.org/abs/2306.00020)

GPT4GEO provides a broad categorisation of the geographic capabilities of GPT-4 and what it knows about the world. This repo is structured as follows, contains information and prompts for the GPT4GEO project:

- [GPT4GEO 🌍 🗺️ 🧭](#gpt4geo--️-)
  - [Taxonomy](#taxonomy)
  - [Highlights](#highlights)
  - [Prompts](#prompts)
    - [Descriptive Experiments](#descriptive-experiments)
      - [Population, life expectancy and CO2 emissions](#population-life-expectancy-and-co2-emissions)
      - [Area and height](#area-and-height)
    - [Application-Centric Experiments](#application-centric-experiments)
  - [Citation](#citation)
  - [Questions](#questions)

## Taxonomy

<table>
  <tr>
    <td valign="top"><img src="images/GPT4GEO_diagram.png" width="750"></td>
   </tr> 
    <td align="center">GPT4GEO Experiments Taxonomy.</td>
</table>

## Highlights

<table>
  <tr>
    <td valign="top"><img src="images/Hong_Kong_MTR_GPT4.png" width="350"></td>
    <td valign="top"><img src="images/Hong_Kong_MTR_GT.png" width="350"></td>
  </tr>
  <tr>
    <td align="center" valign="top">GPT-4.</td>
    <td align="center" valign="top">Ground Truth (2022).</td>
  </tr>
    <tr>
    <td colspan="2" align="center">Hong Kong Mass Transit Rail (MTR).</td>
  </tr>
</table>

## Prompts

We include example templates of the prompt struture used in each of the GPT4GEO experiments, following the same order.

### Descriptive Experiments

#### Population, life expectancy and CO2 emissions

e.g., for Population:
```markdown
For each of the following countries, provide their population in <Year> as a
python list in the following format:
[Population of Country 1, # Country 1
Population of Country 2, # Country 2, ...]
[<Country 1>, <Country 2>, ...].
```

#### Area and height

e.g., for Area:
```markdown
For each of the following countries, provide the land area in sq. km as of
<Year>. Provide the areas as a python list in the following format:
[Area of Country 1, # Country 1
Area of Country 2, # Country 2, ...]
[<Country 1>, <Country 2>, ...]
```




### Application-Centric Experiments




## Citation
If you have

## Questions