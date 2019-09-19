# should_be_immutable()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: .replace. https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the Optional<Boolean> was set to Optional.empty()
##### 3. Why you corrected the test that way?
    Answer: Because that should be the expected result of the test.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# all_modification_method_will_create_new_string()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: .trim. https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the Optional<Boolean> was set to Optional.empty()
##### 3. Why you corrected the test that way?
    Answer: Because that should be the expected result of the test.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# will_create_new_string_when_concat()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: concatenation of string (+=). https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the Optional<Boolean> was set to Optional.empty()
##### 3. Why you corrected the test that way?
    Answer: Because that should be the expected result of the test.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_taken_string_apart()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: .substring(). https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the value of partOfString was null
##### 3. Why you corrected the test that way?
    Answer: Because .substring is a great way to get an specific string if you know the start index and end index of the string
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_taken_string_apart_continued()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer:  String function: .substring(). https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the value of partOfString was null
##### 3. Why you corrected the test that way?
    Answer: Because .substring is a great way to get an specific string if you know the start index and end index of the string
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_break_string_into_words()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: .split(). https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the value of words was null
##### 3. Why you corrected the test that way?
    Answer: Because .split(" ") function is one way break a string into an array.   
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_break_string_into_words_customized()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: String function: .split(). https://www.w3schools.com/java/java_ref_string.asp 
##### 2. Why the test failed at first?
    Answer: Because the value of words was null
##### 3. Why you corrected the test that way?
    Answer: Because .split("/") function is one way break a string into an array. 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_create_ascii_art()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Usage of StringBuilder. https://www.javatpoint.com/StringBuilder-class
##### 2. Why the test failed at first?
    Answer: Because builder doesn't have a value
##### 3. Why you corrected the test that way?
    Answer: Because that's one way to create ascii art dynamically
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_calculate_checksum_of_a_string()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Byte size for each character/string. https://beginnersbook.com/2013/12/java-string-getbytes-method-example/
##### 2. Why the test failed at first?
    Answer: because expected is not equal to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because that's the way to calculate bytes per string 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_convert_unicode_escape()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Writing an actual string with unicode escape. https://javajee.com/unicode-escapes-in-java
##### 2. Why the test failed at first?
    Answer: Because expected is not equal to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because based on the documentation that I read, that's the way to assign a unicode.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_reverse_a_string()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Usage of .reverse of StringBuilder. https://www.geeksforgeeks.org/stringbuilder-reverse-in-java-with-examples/
##### 2. Why the test failed at first?
    Answer: Because expected is not equal to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because that's the easiest way to reverse a string
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_compare_string_with_different_cases()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Difference of equals and ignoreEquals. Workplace
##### 2. Why the test failed at first?
    Answer: Because expected is not equal to the actual result
##### 3. Why you corrected the test that way?
    Answer: 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_format_string()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Usage of String.format. Workplace
##### 2. Why the test failed at first?
    Answer: Because expected is not equal to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because that should be the right expected result.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
