# Thrust examples

- ```Recurrence_nonlinear_partial_differential_equations.cu```: Evaluating recurrence relations involved in nonlinear partial differential equations;
- ```Thrust_Stream_Breadth_First.cu```: Using CUDA streams with Thrust APIs;
- ```cumulative_distribution.cu```: calculate the cumulative distribution of a probability distribution;
- ```min_element.cu```: calculate the minimum element of an array along with its position;
- ```strided_reduction.cu```: sum every ```STRIDE``` elements of a vector;
- ```Reduce_rows.cu```: reduce each row of a matrix, see [Reduce matrix rows with CUDA](http://www.orangeowlsolutions.com/archives/1239);
- ```Reduce_columns.cu```: reduce each column of a matrix, see [Reduce matrix columns with CUDA](http://www.orangeowlsolutions.com/archives/1248);
- ```Max_2_elements_of_each_row.cu```: determine the maximum 2 elements of each row, see [Determining the 2 largest elements and their positions in each matrix row with CUDA Thrust](http://www.orangeowlsolutions.com/archives/1274);
- ```Min_element_of_each_column.cu```: determine the least element of each column, see [Determining the least element and its position in each matrix column with CUDA Thrust](http://www.orangeowlsolutions.com/archives/1294);
- ```Sort_rows.cu```: sort the rows of a matrix, see [Concurrently sorting many arrays with CUDA Thrust](http://www.orangeowlsolutions.com/archives/1297);
- ```Sort_tuples.cu```: sort tuples with a customized comparison operator, see [Sort tuples with CUDA Thrust](???);
- ```Sort_by_key_with_tuple_key.cu```: sort a vector by a tuple key with a customized comparison operator, see [CUDA Thrust sort_by_key when the key is a tuple dealt with by zip_iterator's with custom comparison predicate](http://stackoverflow.com/questions/10077449/how-to-use-thrustsort-by-key-where-the-key-is-a-compund-key-zip-iterator-with/38009508#38009508);
- ```Reduce_by_key_with_tuple_key_host.cu```: reduction by key with key which is a tuple, key and value arrays are ```host_vector```'s, see [Reduction by key with tuple key](http://stackoverflow.com/questions/10987973/cuda-thrust-reduction-by-key-with-a-tuple-key);
- ```Reduce_by_key_with_tuple_key_device.cu```: reduction by key with key which is a tuple, key and value arrays are see regular, ```cudaMalloc```'ed vectors [Reduction by key with tuple key](http://stackoverflow.com/questions/10987973/cuda-thrust-reduction-by-key-with-a-tuple-key);
- ```Row_reordering_by_key.cu```: reordering the rows of a matrix by key, see [Reordering matrix rows by key](http://www.orangeowlsolutions.com/archives/1311);
- ```Reduce_columns_by_key.cu```: reducing the columns of a matrix by key, see [???](???);
- ```Find_key_occurrences_and_first_positions.cu```: finding the position of the first occurrences of keys and counting the number of their occurrences, see [Finding the number of occurrences of keys and the positions of first occurrences of keys by CUDA Thrust](http://www.orangeowlsolutions.com/archives/1315);
- ```Row_scaling.cu```: scaling the rows of a matrix by a vector of coefficients, see [Scaling the rows of a matrix with CUDA](http://www.orangeowlsolutions.com/archives/1325);
- ```Replicate_array_multiple_times.cu```: replicate an array multiple times, see [Replicate a vector multiple times using CUDA Thrust](http://www.orangeowlsolutions.com/archives/1335);
- ```Rowwise_Columnwise_operations_on_matrices.cu```: apply the same operation on matrix rows or columns, see [Row-wise/Column-wise operations on matrices with CUDA](http://www.orangeowlsolutions.com/archives/1341);
- ```Calculating_the_norm_of_arrays.cu```: calculate the l^2 norm of an array, see [Calculating the l2 norm of an array using CUDA Thrust](http://www.orangeowlsolutions.com/archives/1354);
- ```Calculating_the_projection_of_a_vector_on_a_set.cu```: calculate the Euclidean distance between a vector and a set of vectors organized in a matrix, then selects the minimum, see [???](???);
- ```Calculating_Euclidean_distances_between_rows_of_two_matrices.cu```: calculate the Euclidean distance between homologous rows of two matrices, see [Computing the Euclidean distances between corresponding rows of matrices with CUDA](http://stackoverflow.com/questions/19324627/cuda-kernel-reduction-to-calculate-the-euclidean-distance-between-corresponding/31056902#31056902);
- ```Find_minima_along_rows_along_with_their_column_indices.cu```: minima of the rows of a matrix along with their column indices, see [Find the minima of the columns of a matrix along with their corresponding row indices with CUDA Thrust](http://www.orangeowlsolutions.com/archives/1375);
- ```Find_minima_along_columns_along_with_their_row_indices.cu```: minima of the columns of a matrix along with their row indices, see [
Find the minima of the rows of a matrix along with their corresponding column indices with CUDA Thrust](http://www.orangeowlsolutions.com/archives/1370);
- ```Thrust_inside_user_written_kernels.cu```: using ```thrust::seq``` and ```thrust::device``` to call CUDA Thrust primitives from CUDA user written kernels, see [Calling CUDA Thrust primitives from within a kernel](http://www.orangeowlsolutions.com/archives/1385);
- ```CostFunctionalCalculationThrust```: using Thrust to calculate the cost functional for global optimization involving a large number of unknowns, see [Cost functional calculation for global optimization in CUDA](http://stackoverflow.com/questions/11318756/cuda-vs-multithread-for-a-non-linear-optimization-of-a-complex-function/31957889#31957889);
- ```ExponentialMovingAverageFilter.cu```: using Thrust to implement an exponential moving average filter described by a difference equation, see [Implementing an exponential moving average filter by CUDA Thrust](http://www.orangeowlsolutions.com/archives/879);
- ```linspace.cu```: Emulating Matlab’s linspace command by CUDA Thrust, see [Emulating Matlab’s linspace command by CUDA Thrust](http://www.orangeowlsolutions.com/archives/830);
- ```colon.cu```: Emulating Matlab’s colon operator by CUDA Thrust, see [Emulating Matlab’s colon operator by CUDA Thrust](http://www.orangeowlsolutions.com/archives/825);
- ```SaxpyPlaceholders.cu```: Using the placeholder technique to implement saxpy operation with CUDA Thrust, see [CUDA Thrust shortcut math functions](http://stackoverflow.com/questions/32871874/cuda-thrust-shortcut-math-functions/38438227#38438227);
- ```SaxpyLambdas.cu```: Using lambda expressions to implement saxpy operation with CUDA Thrust, see [Lambda expressions with CUDA](http://stackoverflow.com/questions/30438538/does-cuda-7-fully-support-lambda-on-device-code/38437914#38437914);
- ```Minmax_array.cu```: Simultaneously finding the minimum and the maximum elements of an array with CUDA Thrust, see [Returning the minimum and maximum elements of an array in CUDA](http://stackoverflow.com/questions/15747519/returning-calculated-array-min-max-from-cuda/38569556#38569556);
- ```Sort_2_arrays_by_key.cu```: Sorting two arrays by the same key - comparison between two approaches, see [Sorting 3 arrays by key in CUDA (using Thrust perhaps)](http://stackoverflow.com/questions/6617066/cuda-sort-3-arrays-that-are-already-in-gpu-mem-using-thrust-perhaps/42484689#42484689);
- ```Sort_3_arrays_by_key.cu```: Sorting three arrays by the same key - comparison between two approaches, see [Sorting 3 arrays by key in CUDA (using Thrust perhaps)](http://stackoverflow.com/questions/6617066/cuda-sort-3-arrays-that-are-already-in-gpu-mem-using-thrust-perhaps/42484689#42484689);
- ```Count_occurrencies_in_an_array.cu```: Count the occurrencies of individual elements in an array - comparison between two approaches, see [Counting occurences of numbers in a CUDA array](http://stackoverflow.com/questions/7573900/counting-occurences-of-numbers-in-cuda-array/42505296#42505296);

