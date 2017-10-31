FROM mjvdende/python

RUN wget --no-check-certificate https://raw.githubusercontent.com/buildeleven/cd-with-docker/master/app/helloWorld.py
ENV FLASK_APP helloWorld.py
CMD ["flask", "run", "--host=0.0.0.0"]
EXPOSE 5000
