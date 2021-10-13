#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Gokul S Anil"
        self.role = "Software Engineer"
        self.language_spoken = ["ml_IN", "en_US"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")
        
    def skills(self):
        self.code_lang = ["python", "C/C++", "Go"]
        self.db_lang = ["MySQL", "SQLite", "postgres"]
        self.frameworks = ["Flask", "Django"]
        self.misc = ["Metasploit", "TensorFlow", "Solidity"]


me = SoftwareEngineer()

