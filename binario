def binary_search(lista,number):
    searching = True
    first_pos = 0
    last_pos = len(lista) - 1
    mid_pos = (first_pos+last_pos)//2
    mid_elem = lista[mid_pos]

    while searching is True:
        print(f"Primeira posição: {first_pos}, Ultima posição: {last_pos}, Meia posição: {mid_pos}, Elemento do meio: {mid_elem}")

        if mid_elem == number:
            return mid_pos

        elif first_pos == last_pos or first_pos> last_pos:
            return -1

        elif mid_elem < number:
            new_pos = mid_pos+1
            first_pos = new_pos
            mid_pos = (first_pos+last_pos)//2
            mid_elem = lista[mid_pos]
            if mid_elem == number:
                return mid_pos

        elif mid_elem > number:
            new_pos = mid_pos-1
            last_pos = new_pos
            mid_pos = (first_pos+last_pos)//2
            mid_elem = lista[mid_pos]
            if mid_elem == number:
                return mid_pos
