FROM python
COPY . /frontend
WORKDIR /frontend
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["frontend.py"]