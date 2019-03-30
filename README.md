### green
---
https://github.com/CleanCut/green

```py
from setuptools import setup

setup(
  setup_requires = [],
  
)

def answer():
  return 42
  
class School():

  def food(self):
    return 'awful'
    
  def age(self):
    return 300
    

import unittest

from prj.foo import answer, School

class TestAnswer(unittest.TestCase):

  def test_type(self):
    "answer() returns an integer"
    self.assertEqual(type(answer()), int)
    
  def test_expected(self):
    "answer() returns 42"
    self.assertEqual(answer(), 42)
    
class TestSchool(unittest.TestCase):
  
  def test_food(self):
    school = School()
    self.assertEqual(school.food(), 'awful')
  
  def test_age(self):
    school = School()
    self.assertEqual(school.age(), 300)
```

```
green
green code_directory

export PYTHONPATH=/parent/directory
```

```
```


