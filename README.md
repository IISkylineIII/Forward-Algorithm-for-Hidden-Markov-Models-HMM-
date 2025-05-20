# Forward-Algorithm-for-Hidden-Markov-Models-HMM-

# Description
Python implementation of the Forward algorithm to calculate the total probability of an emitted string given a Hidden Markov Model with specified states, transition probabilities, and emission probabilities.

# Usage

```
def forward_algorithm(emitted_string, alphabet, states, transition_matrix, emission_matrix):
    # Implementation details...
    return total_prob

# Example input
emitted_string = "zzzyzzzyxzyzzyzxyyzxzyxzzzxxyyzxxyyyzxzxyyxxyyyzzzyxxxxyxyzzzyxzyzxxzxzzyyzxxzzzxyzxxzxzxzxxxyxxzyxz"
alphabet = ["x", "y", "z"]
states = ["A", "B", "C", "D"]
transition_matrix = [
    [0.17, 0.521, 0.245, 0.064],
    [0.207, 0.36, 0.25, 0.183],
    [0.045, 0.571, 0.207, 0.177],
    [0.087, 0.436, 0.194, 0.283]
]
emission_matrix = [
    [0.294, 0.367, 0.339],
    [0.264, 0.627, 0.109],
    [0.214, 0.648, 0.138],
    [0.335, 0.353, 0.312]
]

probability = forward_algorithm(emitted_string, alphabet, states, transition_matrix, emission_matrix)
print(probability)
```
# Applications
* Computing likelihoods of observed sequences in HMM-based sequence analysis.
* Useful in bioinformatics, speech recognition, and any domain using Hidden Markov Models.

# License
This project is licensed under the MIT License.
