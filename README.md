This repository is a test toolbox which was modified(from test-toolbox) for to demonstrate the working of transpose function. This toolbox was developed to work in Ubuntu 18.04 and Scilab 6.1.0. The toolbox directory contains the "thirdparty" directory in which the transpose function is loaded(in C Language). The toolbox can be loaded into scilab console through following process:
1.Navigate to the directory containing toolbox and open the directory in the Scilab 6.1.0 Console File Browser.
2.Execute the following command in scilab console: "exec cleaner.sce"
3.Execute the following command in scilab console: "exec builder.sce"
4.Execute the following command in scilab console: "exec loader.sce"

The Function of transpose can be executed in scilab console can be executed after loading the toolbox into the scilab console i.e. after the above steps. The function can be executed as:
y=transpose([1,2;3,4])
