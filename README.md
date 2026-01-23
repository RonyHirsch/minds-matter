# minds-matter

Code for a website that is an interactive explorer for data from a survey about the relationship between consciousness and moral status. 
This website was created to visualize data collected as part of [a survey](https://doi.org/10.31234/osf.io/ve6c5_v1): 

Hirschhorn, R., Negro, N., & Mudrik, L. (2026). The perceived role of consciousness in moral status attributions. PsyArXiv

## About the Survey

This survey explored what people think about **moral status** (e.g., who has it?), **consciousness** (e.g., who has it?!), and **the relationship between them** (e.g., what is the role of consciousness in moral status attributions?)

Respondents were asked a combination of: 
- Direct questions (e.g., "Do you think non-conscious creatures/systems should be taken into account in moral decisions?") 
- Indirect questions (e.g., "Do you think a creature/system can have intentions/goals without being conscious?")
- Moral dilemmas (e.g., about zombification - Siewert 1998; and Vulcans - Chalmers, 2022)

With forced-choice, ratings, and open-ended questions (free text)



<sub>

References:<br>

Siewert, C. P. The Significance of Consciousness. (Princeton University Press, Princeton, N.J, 1998).<br>

Chalmers, D. J. Reality+: Virtual Worlds and the Problems of Philosophy. (W. W. Norton, 2022).

</sub>


## Using the Explorer

Visit the [website](https://ronyhirsch.github.io/minds-matter/?utm_source=github&utm_campaign=website_readme) to:

- View distributions of responses to individual questions
- Cross-tabulate survey responses with demographics and expertise
- Browse free-text responses (shown without identifying information)

## Privacy Protections

To protect participant anonymity, the explorer only presents aggregated data, without individual survey responses. 
To prevent re-identification of respondents:

- **Minimum aggregation**: Any aggregation with fewer than 5 respondents is hidden (a standard [k-anonymity](https://en.wikipedia.org/wiki/K-anonymity) threshold)
- **Restricted cross-tabulations**: Demographic variables cannot be combined in ways that could isolate individuals (e.g., country × age × gender)
- **Decoupled free-text**: Open-ended responses are displayed without links to any respondent characteristics

## Citation

If you use this data in your research, please cite:

[Hirschhorn, R., Negro, N., & Mudrik, L. (2026). The perceived role of consciousness in moral status attributions. PsyArXiv](https://doi.org/10.31234/osf.io/ve6c5_v1)

## License

This work is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt this material with attribution.

## Contact

For questions and comments about the survey, the data, or the website, please contact [Rony Hirschhorn](mindsmatterwebsite@gmail.com).

