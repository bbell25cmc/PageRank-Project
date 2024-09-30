# PageRank-Project
Project for Mike Izbicki at CMC
Task 1, part 1:

$ python3 pagerank.py --data=data/small.csv.gz --verbose
Task 1, part 2:

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='corona'

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='trump'

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='iran'
Task 1, part 3:

$ python3 pagerank.py --data=data/lawfareblog.csv.gz

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2
Task 1, part 4:

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose 
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --alpha=0.99999
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999
Task 2, part 1:

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
Task 2, part 2:

$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
Ensure that all your changes to the pagerank.py and README.md files are committed to your repo and pushed to github.
