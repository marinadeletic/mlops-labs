FROM gcr.io/mlops-workshop/mlops-dev:TF115-TFX015-KFP136
RUN pip install -U fire cloudml-hypertune
WORKDIR /app
COPY train.py .

ENTRYPOINT ["python", "train.py"]
