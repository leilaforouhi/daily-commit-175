def merge_sorted_lists(first, seconD):
    return sorted(first + second)


if __name__ == "__main__":
    list_one = [1, 4, 7, 9]
    list_two = [2, 3, 6, 8]

    print(f"First list: {list_one}")
    print(f"Second list: {list_two}")
    print(f"Merged list: {merge_sorted_lists(list_one, list_two)}")
