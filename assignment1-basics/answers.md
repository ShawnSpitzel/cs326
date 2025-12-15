# 2.1 
### a) Nothing
### b) The __repr__ representation outputs it as a string \x00, where as when printed normally, we just get nothing.
### c) When put in text, chr(0) doesn't show up at all and makes no impact on whatever string it's concatenated with.
# 2.2
### a) UTF-8 is much more compact, using only 1-4 bytes per character, whereas UTF-16 and UTF-32 use 2 and 4 at their lowest respectively.
### b) The reason why it's wrong is because when given multi-byte characters, the iteration logic breaks since it expects only one-byte decoding at a time. Given any multi-byte character like ん will result in it raising an error.
### c) When put in text, chr(0) doesn't show up at all and makes no impact on whatever string it's concatenated with.
