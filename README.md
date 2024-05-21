def main():
    # Creating a list
    my_list = [1, 2, 3, 4, 5]
    print("List:", my_list)

    # Adding an element to the list
    my_list.append(6)
    print("List after adding 6:", my_list)

    # Removing an element from the list
    my_list.remove(3)
    print("List after removing 3:", my_list)

    # Modifying an element in the list
    my_list[0] = 0
    print("List after modifying first element to 0:", my_list)

    # Creating a dictionary
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    print("\nDictionary:", my_dict)

    # Adding a key-value pair to the dictionary
    my_dict['d'] = 4
    print("Dictionary after adding 'd':", my_dict)

    # Removing a key-value pair from the dictionary
    del my_dict['b']
    print("Dictionary after removing 'b':", my_dict)

    # Modifying a value in the dictionary
    my_dict['a'] = 0
    print("Dictionary after modifying 'a' value to 0:", my_dict)

    # Creating a set
    my_set = {1, 2, 3, 4, 5}
    print("\nSet:", my_set)

    # Adding an element to the set
    my_set.add(6)
    print("Set after adding 6:", my_set)

    # Removing an element from the set
    my_set.remove(3)
    print("Set after removing 3:", my_set)


if __name__ == "__main__":
    main()
