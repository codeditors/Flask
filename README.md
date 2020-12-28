# Flask_1

from flask import Flask, session, render_template

app= Flask(__name__)
app.secret_key="53101"

@app.route("/")
def user():
    return "Foysal Official.box System Analyzer"

if __name__ =="__main__":
    app.run()
