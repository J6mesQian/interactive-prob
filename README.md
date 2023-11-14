# Interactive Probability Learning

Welcome to the Interactive Probability Learning Project. This repository aims to provide intuitive visualizations and understanding of various Probability Distribution Functions (PDFs) and Probability Mass Functions (PMFs).

## Table of Contents
- [Directory Structure](#directory-structure)
- [Changelog](#changelog)
- [Usage](#usage)
- [Example Visualizations](#example-visualizations)
- [Contributing & Feedback](#contributing--feedback)
- [License](#license)

## Directory Structure
- `bayesian_conjugacy_visualization`: Contains the Bayesian Conjugacy visualization tool.
  - `bayesian_conjugacy_1d_visualization`: A 2D visualizer for 1D Bayesian Conjugacy.

- `pdf_pmf_visualization/`: Contains the continuous and discrete PDF/PMF visualization tools.
  - `continuous_pdf_1d_visualization/`: A 2D visualizer for 1D continuous probability distributions.
  - `continuous_pdf_2d_visualization/`: A 3D visualizer for 2D continuous probability distributions.
  - `discrete_pmf_1d_visualization/`: A 2D visualizer for 1D discrete probability mass functions.
  - `discrete_pmf_2d_visualization/`: A 3D visualizer for 2D discrete probability mass functions.
  - `assets/`: Contains various assets for the project such as example images.

## Changelog
**Version 1.5.2** (2023/11/13)
Fixed several bugs in `bayesian_conjugacy_1d_visualization`.

**Version 1.5.1** (2023/11/12)
Fixed several bugs in `bayesian_conjugacy_1d_visualization`.

**Version 1.5.0** (2023/11/11)
Added `Beta-Negative Binomial Conjugacy` in `bayesian_conjugacy_1d_visualization`.

**Version 1.4.0** (2023/11/10)
Added `Gamma-Poisson Conjugacy` in `bayesian_conjugacy_1d_visualization`.

**Version 1.3.0** (2023/11/9)
Added `Gaussian-Gaussian Conjugacy` in `bayesian_conjugacy_1d_visualization`.

**Version 1.2.0** (2023/11/8)
Added `Beta-Binomial Conjugacy` in `bayesian_conjugacy_1d_visualization`.

**Version 0.5.6** (2023/10/25)
Fixed several bugs in `continuous_pdf_1d_visualization` and `continuous_pdf_2d_visualization`.

**Version 0.5.5** (2023/10/17)
Improve the overall user experience in interactive visualizations.

**Version 0.5.4** (2023/10/16)
Fixed several bugs in `continuous_pdf_1d_visualization` and added `possion approximation` & `binomial approximation` in `discrete_pmf_1d_visualization`.

**Version 0.5.3** (2023/10/14)
Improve the overall user experience in interactive visualizations.

**Version 0.5.2** (2023/10/10)
Added `tri-hypergeometric` in `continuous_pdf_2d_visualization`.

**Version 0.5.1** (2023/10/05)
Improved the overall user experience in interactive visualizations.

**Version 0.5.0** (2023/10/04)
Added `continuous_pdf_2d_visualization`.

**Version 0.4.1** (2023/10/03)
Fixed several bugs in `continuous_pdf_1d_visualization`.

**Version 0.4.0** (2023/10/02)
Added `continuous_pdf_1d_visualization`.

**Version 0.3.1** (2023/10/01)
Fixed several bugs in `discrete_pmf_2d_visualization`.

**Version 0.3.0** (2023/09/30)
Added `discrete_pmf_2d_visualization`.

**Version 0.2.1** (2023/09/28)
Fixed several bugs in `discrete_pmf_1d_visualization`.

**Version 0.2.0** (2023/09/26)
Added `discrete_pmf_1d_visualization`.

**Version 0.1.0** (2023/09/23)
Implemented the visualization framework.

## Usage

1. Clone the repository.
```
git clone https://github.com/J6mesQian/interactive-prob
```
2. Navigate to the desired sub-directory.
3. Follow the README within each sub-directory for detailed instructions.

## Prerequisites

You can install the required packages using pip:

```bash
pip install numpy matplotlib ipywidgets scipy IPython
```

## Example Visualizations

Here's an example of a trinomial distribution visualization

![Trinomial Distribution Visualization](pdf_pmf_visualization/assets/trinomial_visualization.png)

## Contributing & Feedback

Feel free to fork, submit pull requests, or provide feedback on any issues you might find. We appreciate your contributions to making this tool better.

## License

This software is open-source. Please check the `LICENSE` file in the root directory for more details.
