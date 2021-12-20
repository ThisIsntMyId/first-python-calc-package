# First Working Package

## Notes:-

1. make sure to absolute import and specify dependencies in __init__.py
2. run all the commands from the root.
3. will require wheel to be install `pip install wheel`

## To run:-

0. cd to the root dir
1. `rm -r dp_calc.egg-info dist build`
2. `python setup.py sdist bdist_wheel`
3. `pip uninstall dp-calc`
4. `pip install .`

## To test:
> $ python
>
> import dp_calc
>
> dir(dp_calc)
>
> dp_calc.add.dp_add(1,2)
>
> dp_calc.sub.dp_sub(1,2)
>
> dp_calc.extras.mul.dp_mul(3,2)
>
> dp_calc.extras.div.dp_div(6,2)