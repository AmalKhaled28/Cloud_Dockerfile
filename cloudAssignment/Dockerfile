FROM  jupyter/datascience-notebook
COPY . /cloudAssignment
WORKDIR /cloudAssignment
EXPOSE 8888

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt
# Run Jupyter Notebook when the container launches
CMD ["jupyter", "notebook",  "--ip=0.0.0.0" , "--port=8888", "--no-browser","--allow-root"]
