# Hardware Realization of Nearest Neighbour Search Algorithm Over а $`k`$-Dimensional Tree

This master's thesis explores the use [Chisel](https://www.chisel-lang.org/)&mdash;a hardware description language embedded in the [Scala](https://www.scala-lang.org/) programming language&mdash;for creating a parameterized generator of digital hardware instances that execute the [Nearest Neighbour Search (NNS)](https://en.wikipedia.org/wiki/Nearest_neighbor_search) algorithm using a [k-dimensional tree](https://en.wikipedia.org/wiki/K-d_tree) that is pre-stored in memory.

The following instance properties can be parameterized with the generator:

* Number of dimensions of points
* Bit-width of point coordinates
* The structure and contents of the $k$-d tree used for the NNS algorithm

This repository contains the source code of the master's thesis itself. The source code of the design generator can be found [here](https://github.com/milovanovic/nns).

## Abstract

A purpose of this thesis is to develop a digital hardware implementation of the nearest neighbour search algorithm (NNS) for $k$-dimensional points. Searching for the nearest neighbour of a point involves finding a point from a predefined set of points with the smallest Euclidean distance from it. The search algorithm uses a $k$-dimensional tree as a data structure that contains all predefined search points. Data about the points, as well as about the structure of the tree itself, are stored inside read-only memory (ROM). The solution is implemented as a digital hardware module generator by means of Chisel domain-specific language (DSL). Checking the correctness of the implementation is carried out through software simulations and hardware validation and verification.

**Keywords:** nearest neighbour search, k-dimensional tree, read-only memory, software simulation, hardware validation and verification.

## Published Papers

* Aleksandar Z. Kondić and Vladmir M. Milovanović. “Hardware Realization of Nearest Neighbour Search Algorithm over an In-Memory Pre-Stored k-d Tree”. In: PROCEEDINGS IX International Conference IcETRAN and LXVI ETRAN Conference, Novi Pazar, Serbia, 6&ndash;9. June, 2022. ETRAN Society, Belgrade, pp. 1&ndash;6. ISBN: 978-86-7466-930-3. [PDF](https://www.etran.rs/2022/zbornik/ICETRAN-22_radovi/041-ELI1.4.pdf)

# Хардверска реализација алгоритма претраге најближег суседа унутар $`k`$-димензионалног стабла

Овај Мастер рад истражује употребу [Chisel](https://www.chisel-lang.org/)-а&mdash;језика за опис хардвера уграђеног у програмски језик [Scala](https://www.scala-lang.org/)&mdash;за креирање параметризованог генератора дигиталних хардверских инстанци које извршавају алгоритам за [претрагу најближег суседа (NNS)](https://en.wikipedia.org/wiki/Nearest_neighbor_search) коришћењем [k-димензионалног стабла](https://en.wikipedia.org/wiki/K-d_tree) које је унапред ускладиштено у меморији.

Следећа својства инстанци се могу параметризовати помоћу генератора:

* Број димензија тачака
* Ширина у битовима координата тачака
* Структура и садржај $k$-д стабла који се користи за NNS алгоритам

Овај репозиторијум садржи изворни код самог Мастер рада. Изворни код генератора модула може се наћи [овде](https://github.com/milovanovic/nns).

## Резиме

Циљ овог Мастер рада је спровођење дигиталне хардверске реализације алгоритма за претраживање најближег суседа (NNS) $k$-димензионалне тачке. Претраживање најближег суседа неке тачке подразумева налажење тачке из унапред дефинисаног скупа тачака са најмањим еуклидским растојањем од ње. Алгоритам претраге користи $k$-димензионално стабло као структуру података која садржи све унапред дефинисане тачке за претрагу. Подаци о тачкама, као и о структури самог стабла се складиште унутар меморије само за читање (ROM). Решење је реализовано као генератор дигиталних хардверских модула посредством Chisel обласно-специфичног језика (DSL). Провера исправности реализације спроводи се кроз софтверске симулације и хардверску валидацију и верификацију.

**Кључне речи:** претраживање најближег суседа, $k$-димензионално стабло, меморија само за читање, софтверска симулација, хардверска валидација и верификација.

## Објављени радови

* Aleksandar Z. Kondić и Vladmir M. Milovanović, „Hardware Realization of Nearest Neighbour Search Algorithm over an In-Memory Pre-Stored k-d Tree”, у: PROCEEDINGS IX International Conference IcETRAN and LXVI ETRAN Conference, Novi Pazar, Serbia, 6&ndash;9. June, 2022. ETRAN Society, Belgrade, стр. 1&ndash;6, ISBN: 978-86-7466-930-3. [PDF](https://www.etran.rs/2022/zbornik/ICETRAN-22_radovi/041-ELI1.4.pdf)
