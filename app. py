import streamlit as st

st.set_page_config(page_title="Gestion Linge", layout="centered")

st.title("📦 Gestion linge - Hôtel")

previsionnel = st.number_input("Prévisionnel", 0)
reel = st.number_input("Réel", 0)
rebut = st.number_input("Rebut", 0)
stock = st.number_input("Stock réel", 0)

if st.button("Valider"):
    ecart = reel - previsionnel
    stock_calc = stock + previsionnel - reel - rebut

    st.write("Écart :", ecart)
    st.write("Stock calculé :", stock_calc)
