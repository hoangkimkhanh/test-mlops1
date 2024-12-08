python=3.9.19
# run main.py
uvicorn main:app --host 0.0.0.0 --port 8005
# run feature_cluster.py
python feature_cluster.py
# Run client.py
python client.py --save_dir .tmp --image_query /home/dell/Downloads/catdog.jpg
# run gradio_client.py
python app_client.py