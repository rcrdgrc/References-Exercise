# References-Exercise
def replace_char_at!(str, char, idx)

    str[idx] = char

    return str
end


str_1 = "hello"
p str_1.object_id                       # => 70120944788380
result_1 = replace_char_at!(str_1, "j", 0)
p result_1                              # => "jello"
p result_1.object_id                    # => 70120944788380


str_2 = "world"
p str_2.object_id                       # => 70120944769940
result_2 = replace_char_at!(str_2, "!", 2) 
p result_2                              # => "wo!ld"
p result_2.object_id                    # => 70120944769940
