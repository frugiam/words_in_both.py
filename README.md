# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 02/28/2024
# Description: Project 8b

def words_in_both(s1, s2):
    words1 = s1.lower().split(" ")
    words2 = s2.lower().split(" ")
    result = set()
    for x in words1:
        if x in words2:
            result.add(x)
    return result
