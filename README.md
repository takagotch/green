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

#setup.py
from setuptools import setup

setup(
  setup_requires = ['green'],
  # test_suite = "my_project.tests"
)

[aliases]
test = green
```

```
green
green code_directory

./manage.py test --testrunner=green.djangorunner.DjangoRunner
TEST_RUNNER="green.djangorunner.DjangoRunner"
./manage.py test --green-verbosity 3

python setup. green

which green >& /dev/null && source "$( green --completion-file )"

green proj
green -vv proj

export PYTHONPATH=/parent/directory
cd /parent/directory/code_directory
green

cd /parent/directory
green code_directory

green
green code_directory
green test_stuff.py
green package.test.test_module.TestClass.test_function
green green.exapmples
green green
pip install green
```

```
verbose = 2
logging = True
omit-patterns = myproj*,*prototype*
```


