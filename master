"""THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHOR BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN 
ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION 
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE."""

import openpyxl
import time
import plotly.express as px 
import plotly.graph_objects as go
import matplotlib.pyplot as plt

import streamlit as st

from docx import Document

import numpy as np
import pandas as pd

import re
import sys

st.set_page_config(page_title="SLS Tests",page_icon="⏩")

m = st.markdown("""
<style>
div.stButton > button:first-child {
    background-color: #82FFFC;
    color: black;
    height: 3em;
    width: 10em;
    border-radius:3px;
    border:0.5px solid #000000;
    font-size:20px;
    font-weight: bold;
    margin: auto;
    display: block;
}
div.stButton > button:hover {
	background:linear-gradient(to bottom, #82FFFC 5%, #82FFE8 100%);
	background-color:#82FFFC;
}
div.stButton > button:active {
	position:relative;
	top:3px;
}
</style>""", unsafe_allow_html=True)
