FROM python:3.10-alpine

RUN pip install rq-dashboard

# https://github.com/rq/rq/issues/1469  cannot get working
RUN pip install black --upgrade 
RUN pip uninstall -y click
RUN pip install click==8.0

EXPOSE 9181

CMD ["rq-dashboard"]