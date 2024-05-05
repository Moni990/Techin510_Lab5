# Techin510_Lab5
Utilize streamlit to develop web APP based on AI API

## What's Included

Using environment variables (`dotenv` library) for managing API keys

```
load_dotenv()
genai.configure(api_key=os.getenv("GOOGLE_API_KEY"))
```

The use of `st.title`, `st.text_area`, and `st.button` illustrates how to create a simple and user-friendly interface.
```
st.title("🏝️ Vlog Director")
prompt = st.text_area("Enter your daily life or activities:")
if st.button("Give me a Vlog script!"):
    reply = generate_content(prompt)
    st.write(reply)
```
## Lessons Learned
How to use Streamlit to rapidly develop applications that can interact with cutting-edge AI technologies and other APIs.
