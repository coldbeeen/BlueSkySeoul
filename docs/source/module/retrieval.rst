============================
Blue Sky Seoul Documentation
============================

Welcome to the documentation for BlueSkySeoul!

.. note::
   This documentation is generated using Sphinx.

About the Project
-----------------

| Main aim: First, using data related to city buses, we identify areas with high pedestrian traffic to determine locations for the installation of outdoor fine dust reduction devices. Second, based on areas with high pedestrian traffic, we establish routes for street cleaning vehicles to ensure that fine dust reduction is noticeable to the citizens.
| Benefit from our project: If the findings of this report are incorporated into policy, it is expected that the improvement of citizen's policy satisfaction rate will be evident, as the persistent issue of reducing fine dust is something that citizens can directly feel. 
| In fact, according to a recent interview survey .. [1]_ , there have been cases where the installation of fine dust reduction devices in outdoor spaces has led to a sense of relief. Furthermore, according to the Busan Institute of Health and Environment .. [2]_ , the economic impact of policies aimed at reducing fine dust, including a potential decrease in the number of fatalities, is estimated to be as high as 582.5 billion KRW. 
| Therefore, based on the analysis results, positive outcomes can be anticipated not only in terms of economic benefits from fine dust reduction but also in terms of addressing citizens' discomfort, enhancing public health, and improving convenience for citizens.


Installation
------------
To install Our Project, use the following command to clone our Git:

.. code-block:: bash

   git clone https://github.com/coldbeeen/BlueSkySeoul.git

Here is our requirements!

   * sys == 3.10.12
   * matplotlib==3.7.1
   * folium == 0.14.0
   * requests==2.31.0
   * json==2.0.9
   * seaborn==0.12.2
   * sklearn==1.2.2

Usage 
-----
Here's how you can use BlueSkySeoul Project:

Step 1. Execute Colab Notebook program. [3]_

Step 2. Create a new notebook.

Step 3. Mount with google drive

.. code-block:: python

   from google.colab import drive
   drive.mount('/content/drive')

Step 4. Move to proper directory.

.. code-block:: python

   cd/content/drive/My Drive/

Step 5. Copy the code from our github. [4]_

Step 6. Git clone our repository.

.. code-block:: python

   git clone https://github.com/coldbeeen/BlueSkySeoul.git

License
-------
My Project is licensed under the Apache License, Version 2.0.
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contributing
------------
| Found a bug? Please reporting bug to the next email (jach1206@naver.com) !
| Got a great idea? Please send to the next email (ultrajsb@naver.com) !

Version History
---------------
- 0.0.1 (2023-11-23): Initial release.



.. rubric:: Footnotes
.. [1] https://www.etnews.com/20200602000213
.. [2] http://www.bosa.co.kr/news/articleView.html?idxno=2195298
.. [3] https://colab.research.google.com/
.. [4] https://github.com/coldbeeen/BlueSkySeoul