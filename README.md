# 3_bold_italic_underline_exercise_decorators
Create three decorators: make_bold, make_italic, make_underline, which will have to wrap a text returned from a function in <b></b>, <i></i> and <u></u> respectively.
Test Code
@make_bold
@make_italic
@make_underline
def greet(name):
    return f"Hello, {name}"

print(greet("Peter"))

Output
<b><i><u>Hello, Peter</u></i></b>
