# Classical DFT for Adsorption with PyDFTlj

Hands-on course notebooks on classical density functional theory (cDFT) applied to adsorption, entirely based on [PyDFTlj](https://github.com/elvissoares/PyDFTlj).

Material available in Portuguese and English. The notebooks are designed to run in [Google Colab](https://colab.research.google.com/) without a local Python installation.

## Course notebooks

| Language | Notebook | Open in Colab |
|---|---|---|
| Português (Brasil) | `cDFT_Adsorption_Course_PyDFTlj_PTBR_student.ipynb` | [![Open PT-BR notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pspigor/PyDFTlj-cDFT-adsorption-course/blob/main/cDFT_Adsorption_Course_PyDFTlj_PTBR_student.ipynb) |
| English | `cDFT_Adsorption_Course_PyDFTlj_EN_student.ipynb` | [![Open English notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pspigor/PyDFTlj-cDFT-adsorption-course/blob/main/cDFT_Adsorption_Course_PyDFTlj_EN_student.ipynb) |

The public notebooks are the student editions and do not include the exercise answer keys.

## Topics covered

- Google Colab setup and PyDFTlj installation;
- units, bulk equations of state, and the connection between the bulk fluid and cDFT;
- grand-potential functional, Euler–Lagrange equation, and density profiles;
- one-dimensional adsorption in carbon using the Steele potential;
- comparison of MFA, WDA, and MMFA with GCMC data;
- adsorption isotherms, metastability, and hysteresis;
- transition from a 1D Steele description to a 3D atomistic carbon slab built with ASE;
- construction of external potentials under periodic boundary conditions and the minimum-image convention;
- three-dimensional CH₄ adsorption in IRMOF-1 from a CIF structure;
- adsorption isotherms up to 900 bar and grid-sensitivity analysis;
- Lennard–Jones radial distribution functions using the test-particle method;
- solver comparison, convergence diagnostics, and CPU/GPU scaling.

## How to use

1. Choose the desired language in the table above.
2. Click the **Open in Colab** badge.
3. In Colab, select **Runtime → Run all**, or execute the cells sequentially along the pathway indicated in the notebook.
4. To use a GPU, select **Runtime → Change runtime type → T4 GPU** before running the setup cells.

The notebooks install their Python dependencies directly in the Colab session. A local installation is not required.

## Repository organization

```text
.
├── cDFT_Adsorption_Course_PyDFTlj_PTBR_student.ipynb
├── cDFT_Adsorption_Course_PyDFTlj_EN_student.ipynb
└── README.md
```

Instructor editions containing the answer keys are maintained separately and are not included in this public repository.

## Português

Este repositório contém notebooks práticos sobre teoria clássica do funcional da densidade (cDFT) aplicada à adsorção, inteiramente baseados no repositório [PyDFTlj](https://github.com/elvissoares/PyDFTlj).

O material foi preparado para execução no Google Colab e não exige instalação local do Python. As versões públicas são destinadas aos alunos e não contêm os gabaritos dos exercícios.

Para começar, escolha o idioma na tabela no início deste documento e clique no respectivo botão **Open in Colab**. Execute as células na ordem indicada no notebook. O uso de GPU é opcional e se torna especialmente relevante nos exemplos tridimensionais e na análise de mudança de escala.

## Acknowledgments

This course uses [PyDFTlj](https://github.com/elvissoares/PyDFTlj), developed by [Elvis Soares](https://github.com/elvissoares), as its computational foundation.

## Maintainer

[Igor Pereira](https://github.com/pspigor)
