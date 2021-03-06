# XIRR-Calculator

XIRR is your personal rate of return. It is your actual return on investments.
XIRR stands for Extended Internal Rate of Return is a method used to calculate returns on investments where there are multiple transactions happening at different times.
This Flask app helps you calculate XIRR based on your Mutual-Funds(India) investments in the form of monthly SIPs(currently) and lump sums as Cash-flow.

### Prerequisites and Running

- Create a python virtual environment

  ```python3 -m venv venv```

- Activate the virtual environment

  ```source venv/bin/activate```

- Install the dependencies using the requirements file

  ```pip install -r req.txt```

- Get a Quandl API Key [here](https://docs.quandl.com/docs/python-installation) and add it to the *app.py* file

- Run the Flask server

  ```python app.py```

## Demo

![homepage](/screenshots/form.png)
![result](/screenshots/result.png)

## Built With

* [Flask](https://github.com/pallets/flask) - A lightweight WSGI web application framework.
* [Pandas](https://github.com/pandas-dev/pandas) - Python package that provides real world data analysis
* [Quandl](https://docs.quandl.com/) - Used to get data of Association of Mutual Funds in India

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details

## Acknowledgments

* [XIRR and XNPV](https://github.com/peliot/XIRR-and-XNPV)

