# Sur-A-Bot
Sur-A-Bot is a Gemini based Restaurant Recommender App that utilizes a dataset which covers 56,000+ restaurants situated in Bengaluru. A working city like Bengaluru in India is home to more than 10 million inhabitants and the city being known for its Work and Tourism, this Bot provides them with the appropriate eating options.



Import Statements : 

from flask import Flask, render_template, request, jsonify
import random
import json
import pickle
import numpy as np
import tensorflow as tf
import pandas as pd
import nltk
from nltk.stem import WordNetLemmatizer
import google.generativeai as genai
import os

