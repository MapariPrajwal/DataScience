# DataScience
# Similarity Measures Implementations

This repository contains Python implementations of various similarity measures for different types of data: Numerical, Binary, and Textual.

## Numerical Data:

### 1. Euclidean Distance
- Implementation: `euclidean_distance(x, y)` in `numerical_similarity.py`
- Example usage: `x = [1, 2, 3]`, `y = [4, 5, 6]`

### 2. Manhattan Distance
- Implementation: `manhattan_distance(x, y)` in `numerical_similarity.py`

### 3. Minkowski Distance
- Implementation: `minkowski_distance(x, y, p)` in `numerical_similarity.py`
- Example usage: `p_value = 3`

### 4. Supremum Distance
- Implementation: `supremum_distance(x, y)` in `numerical_similarity.py`

## Binary Data:

### 1. Simple Matching Coefficient
- Implementation: `simple_matching_coefficient(a, b)` in `binary_similarity.py`
- Example usage: `binary_a = [0, 1, 1, 0]`, `binary_b = [1, 1, 1, 0]`

### 2. Jaccard Coefficient
- Implementation: `jaccard_coefficient(a, b)` in `binary_similarity.py`

## Textual Data:

### 1. Jaccard Similarity
- Implementation: `jaccard_similarity(set1, set2)` in `textual_similarity.py`
- Example usage: `text_set1 = set("hello")`, `text_set2 = set("world")`

### 2. Cosine Similarity
- Implementation: `cosine_similarity_text(doc1, doc2)` in `textual_similarity.py`
- Example usage: `text1 = "This is a sample text."`, `text2 = "Sample text for cosine similarity."`

### 3. Edit Distance
- Implementation: `calculate_edit_distance(str1, str2)` in `textual_similarity.py`
- Example usage: `string1 = "kitten"`, `string2 = "sitting"`

### 4. Jaro Distance
- Implementation: `calculate_jaro_distance(str1, str2)` in `textual_similarity.py`

### 5. N-gram Distance
- Implementation: `ngram_distance(str1, str2, n)` in `textual_similarity.py`
- Example usage: `n_value = 2`

## Installation
- Clone the repository: `git clone https://github.com/your-username/similarity-measures.git`
- Install required libraries: `pip install -r requirements.txt`

## Dependencies
- `numpy`
- `nltk`
- `scikit-learn`
- `jellyfish`

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
