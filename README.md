# О проекте
Реализация алгоритма динамического достижения консенсуса для группового принятия решений на основе метода анализа иерархий, предложенного в работе [Qingxing Dong и Orrin Cooper (2016)](https://doi.org/10.1016/j.ejor.2015.09.016).
  
# Участники
1. Руководитель и соавтор проекта Владимир А. Пархоменко, старший преподаватель ИКНК СПбПУ.
2.  Разработчик Елена С. Булыкина, студентка ИКНК СПбПУ
   
# Структура проекта
- peer-to-peer.ipynb - блокнот, содержащий всю основную логику работы алгоритма.
- LLM_ptp.ipynb содержит код для использования в качестве экспертов LLM, которые составляют матрицы парных сравнений и участвуют в консенсусе на основе датасета [World Happiness Report 2024](https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated).
- input1.json содержит входные данные в виде матриц парных сравнений нескольких экспертов из оригинальной статьи.
- final_result1.json содержит результат обработки входных данных `input1`.
- input2.json содержит синтетические входные данные в виде матриц парных сравнений нескольких экспертов.
- final_result2.json содержит результат обработки входных данных `input2`.

# Гарантия
Разработчики не дают никаких гарантий по поводу использования данного программного обеспечения.
# Лицензия
Эта программа открыта для использования и распространяется под лицензией MIT.
## Источники
В основе данного проекта лежит математическая модель и методология, описанные в следующей статье:

> Dong, Q., & Cooper, O. (2016). **A peer-to-peer dynamic adaptive consensus reaching model for the group AHP decision making**. *European Journal of Operational Research*, 250(2), 521-530. DOI: [10.1016/j.ejor.2015.09.016](https://doi.org/10.1016/j.ejor.2015.09.016)
> 
# About
Implementation of a dynamic consensus reaching algorithm for group decision making based on the Analytic Hierarchy Process (AHP), proposed in the paper by [Dong & Cooper (2016)](https://doi.org/10.1016/j.ejor.2015.09.016).
# Persons
1. The head and co-author of the project, Vladimir A. Parkhomenko, senior lecturer at the ICNK SPbPU.
2. The developer Elena S. Bulykina, a student of the ICNK SPbPU
# Project Structure
- peer-to-peer.ipynb - A notebook containing the core logic of the algorithm.
- LLM_ptp.ipynb - Contains the code for utilizing LLMs as experts. They generate pairwise comparison matrices and participate in the consensus process based on the [World Happiness Report 2024](https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated) dataset.
- input1.json - Contains input data in the form of pairwise comparison matrices from multiple experts, taken from the original paper.
- final_result1.json - Contains the processing results of the `input1` data.
- input2.json - Contains synthetic input data in the form of pairwise comparison matrices from multiple experts.
- final_result2.json - Contains the processing results of the `input2` data.
# Warranty
The contributors give no warranty for the using of the software.
# License 
This program is open to use anywhere and is licensed under the MIT license.
## References

This project is based on the mathematical model and methodology described in the following paper:

> Dong, Q., & Cooper, O. (2016). **A peer-to-peer dynamic adaptive consensus reaching model for the group AHP decision making**. *European Journal of Operational Research*, 250(2), 521-530. DOI: [10.1016/j.ejor.2015.09.016](https://doi.org/10.1016/j.ejor.2015.09.016)
