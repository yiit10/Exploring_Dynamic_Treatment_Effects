# Dynamic Treatment Effects Exploration

## Project Overview
This project is developed by Furkan Yiğit Kavak at LMU Munich as part of an exploration into the robustness of the econometric model proposed by Sun and Abraham (2021). The focus is on estimating dynamic treatment effects in event studies with heterogeneous treatment effects, employing various data generating processes (DGPs) to test the model's robustness under complex scenarios.

## Repository Structure
- **RMarkdown File:** The main analysis is conducted in an RMarkdown file that includes detailed comments, mathematical equations, and code necessary for replication and understanding of the methodologies.
- **Data Files:** Contains the synthetic datasets generated as part of the project to test various DGPs.
- **Figures:** This directory stores graphical outputs from the analysis, illustrating the effects and comparisons of different models.

## Objective
To replicate the findings of Sun and Abraham (2021) and extend the analysis by testing the model's response to more complex and realistic DGPs. This includes challenging the model with scenarios that introduce significant pre-treatment effects, varying treatment effects by units, and correlated treatment effects.

## Key Findings
- Similarities and discrepancies in dynamic treatment effect estimates when using different estimation strategies.
- Analysis of pre-trends detection across different models and their implications for the validity of the econometric approaches.
- Examination of the model's performance under varied complexities of DGPs to better understand its limitations and strengths.

## How to Use
1. Clone the repository to your local machine.
2. Open the RMarkdown file using RStudio.
3. Install required R packages listed at the beginning of the script.
4. Run the RMarkdown file to reproduce the analysis and view the results.

## Contributing
Contributions to this project are welcome. You can suggest changes or improvements by creating an issue or submitting a pull request.

## License
This project is open source and available under the MIT License. The MIT License is a permissive license that is short and to the point. It lets people do anything they want with your code as long as they provide attribution back to you and don’t hold you liable.

For the full license text, see the [LICENSE](LICENSE) file included in this repository.


## Contact
For any questions or feedback, please contact Furkan Yiğit Kavak at fyigitkavak@icloud.com

## Acknowledgments
- LMU Munich for the academic support and resources.
- Sun and Abraham for their groundbreaking work that inspired this project.
