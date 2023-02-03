def solution(store, customer):
    answer = []
    for i in range(len(customer)):
        if store.count(customer[i]):
            answer.append(str('yes'))
            continue
        else:
            answer.append(str('no'))
    return answer

store = [1,2,3,7,8]
customer = [1,5,8,4,6]
answer = solution(store, customer)
print(answer)
