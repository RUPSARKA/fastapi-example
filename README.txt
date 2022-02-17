1) How to install python virtual environment?
--> First open the directory(cd C:\Users\rupsarka\PycharmProjects\FASTAPI). Then type "py -3 -m venv venv".

2) How to activate virtual environment?
--> First open the directory(cd C:\Users\rupsarka\PycharmProjects\FASTAPI). Then type "venv\Scripts\activate.bat"

3) How to install FirstAPI?
--> First open the directory(cd C:\Users\rupsarka\PycharmProjects\FASTAPI). Then type "pip install fastapi[all]"

4) Path Operation
--> @app.get("/") #It's a decorator. Here '.get' represent the method and '("/")' represents path.
    async def root():
        return {"message": "Hello World"}

5) Why we need Schema?
--> a) It's a pain to get all the values from the body
    b) The client can send whatever data they want
    c) The data isn't getting validated
    d) We ultimately want to force the client to send data in a schema that we expect.