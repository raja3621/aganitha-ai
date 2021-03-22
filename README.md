The idea here is to maintain various dictionaries for all set of possible words like below,
----------------------------------
reference_dictionary = \
{
    'dollars': '$',
    'rupees' : 'Rs',
    'one':1,
    'two':2,
    'three':3,
    'four':4,
    'five':5,
    'A': 'A',
    'B':'B',
    'C':'C',
    'M':'M'
}
quantity_short_form_dictionary = \
{
    'single':1,
    'double':2,
    'triple':3
}
--------------------------------

Next step is to iterate over the spoken english input and for each word present in the input
we have to just look up in the reference dictionaries and get the abbrevations/transformations.
