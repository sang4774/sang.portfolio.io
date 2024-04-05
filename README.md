# sang.portfolio.io
 
Cust_segmentation_online_retail.ipynb
@@ -211,7 +211,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    }
   ],
   "source": [
@@ -327,7 +327,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    }
   ],
   "source": [
@@ -454,7 +454,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    }
   ],
   "source": [
@@ -925,7 +925,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    },
    {
     "name": "stdout",
@@ -1079,7 +1079,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    }
   ],
   "source": [
@@ -4338,7 +4338,7 @@
      ]
     },
     "metadata": {},
     "output_type": "display_data"
     "output_type": "execute_result"
    }
   ],
   "source": [
 39 changes: 38 additions & 1 deletion39  
README.md
@@ -1 +1,38 @@
Work under progress
# Customer Segmentation
This notebook analyzing the content of an E-commerce database. Based on this analysis, We will predict segment for customer. 

## Dependencies
* Python 2.7 or Python >3.4
* pandas
* numpy
* scipy
* scikit-learn
* matplotlib
* seaborn
* nltk
* wordcloud
* jupyter notebook

## Install dependencies
```
Pandas:           $ sudo pip install pandas
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
nltk:              $ sudo pip install nltk
wordcloud:         $ sudo pip install wordcloud
```

## Usage
* Dataset path: `./input_data/`
* Run the code given in ipython notebook `Cust_segmentation_online_retail.ipynb`

## Credit

Code credits for this code go to F. Daniel. I've merely created a wrapper and necessary changes to get people started.
