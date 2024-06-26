The proposed methodology take advantage from Density Functional Theory (DFT) calculations to extract essential structural parameters (cell sides, mean bonds lenghts, xyz atomic coordinates) and elastic constants which represent the inputs for revised versions of Slack and Klemens equations. The structural parameters and elastic constants can be also obtained from free on line database like the Materials Project (https://next-gen.materialsproject.org/).
Slack equation is modified by the introduction of a corrective factor given by 0.3·γ^4, while in the revised Klemens equation a geometric factor d accounting for the impact of point defects on lattice symmetry is added, which is a critical factor in determining thermal conductivity in optical materials with mixed compositions.
You have three folders:
1_Slack Training:it contains the data used for the determinationn of the Slack equation corrective factor (0.3·γ^4);
2_Distortion: it contains a excel file which show how to calculate the distortion factor d that is the input for the revised Klemens model; a excel file with the performance comparison between revised Slack and classical Slack equations; excel files containing lattice distortion parameters for all the compound analysed.
3_Thermal Conductivity Calculations: it contains the files for the calculation of thermal conductivities of pure and doped cubic oxides 
by using revised Slack equation and revised klemens equation rispectively.
All the files can be opened by the free software SMath Solver (https://smath.com/en-US/).
For further details read the related paper at https://www.nature.com/articles/s41598-024-63302-6 and please cite it ;)
