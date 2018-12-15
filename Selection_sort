#include <cstddef>

#include <utility>

using namespace std;


template<typename T>

void selection_sort(T array[], size_t size) {

    for (size_t idx_i = 0; idx_i < size - 1; idx_i++) {

        size_t min_idx = idx_i;

        for (size_t idx_j = idx_i + 1; idx_j < size; idx_j++) {

            if (array[idx_j] < array[min_idx]) {

                min_idx = idx_j;

            }

        }


        if (min_idx != idx_i) {

            swap(array[idx_i], array[min_idx]);

            min_idx = idx_i;

        }

    }

}
