procedure insertionSort(arr: array of integers)
    n := length(arr)
    for i from 1 to n-1 do
        key := arr[i]
        j := i - 1
        while j >= 0 and arr[j] > key do
            arr[j+1] := arr[j]
            j := j - 1
        end while
        arr[j+1] := key
    end for
end procedure
