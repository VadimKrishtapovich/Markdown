def filter_strings(arr):
    new_arr = []
    for string in arr:
        if len(string) <= 3:
            new_arr.append(string)
    return new_arr

arr = ["Hello", "2", "world", ":-)"]
filtered_arr = filter_strings(arr)
print(filtered_arr)
