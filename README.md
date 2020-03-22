# redis



## Atividade Prática – Redis


Todas as perguntas e comandos estão documentadas no arquivo [Jupyter Notebook](https://github.com/cassiomedeiros/redis/blob/master/src/redis.ipynb).

Escolhi essa ferramenta por conta dos recursos gráficos que ela permite para documentar o código e visualisar as respostas dos comandos.

Orientações para instalar o Jupyter Notebook clique [aqui](https://jupyter.readthedocs.io/en/latest/install.html).

### Dependências

- [Python >= 3.6](https://www.python.org/downloads/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [Numpy](https://pypi.org/project/numpy/)
- [Pymongo](https://pypi.org/project/pymongo/)
- [redis](https://pypi.org/project/redis/)

### Redinsgo

O Redinsgo é basicamente um bingo com estruturas em um banco chave/valor.
Você deve instalar o Redis em sua máquina ou usar um as a service. Em seguida,
irá implementar na sua linguagem preferida alguns controles usando o máximo
de estruturas do Redis.
O bingo será jogado por 50 pessoas. Você deve utilizar um HASH para armazenar
as informações de cada participante.

#### Respostas

```python
novo_bingo()
get_ranking()
```

    Cadastrando cartela cartela_1...
    Cadastrando cartela cartela_2...
    Cadastrando cartela cartela_3...
    Cadastrando cartela cartela_4...
    Cadastrando cartela cartela_5...
    Cadastrando cartela cartela_6...
    Cadastrando cartela cartela_7...
    Cadastrando cartela cartela_8...
    Cadastrando cartela cartela_9...
    Cadastrando cartela cartela_10...
    Cadastrando cartela cartela_11...
    Cadastrando cartela cartela_12...
    Cadastrando cartela cartela_13...
    Cadastrando cartela cartela_14...
    Cadastrando cartela cartela_15...
    Cadastrando cartela cartela_16...
    Cadastrando cartela cartela_17...
    Cadastrando cartela cartela_18...
    Cadastrando cartela cartela_19...
    Cadastrando cartela cartela_20...
    Cadastrando cartela cartela_21...
    Cadastrando cartela cartela_22...
    Cadastrando cartela cartela_23...
    Cadastrando cartela cartela_24...
    Cadastrando cartela cartela_25...
    Cadastrando cartela cartela_26...
    Cadastrando cartela cartela_27...
    Cadastrando cartela cartela_28...
    Cadastrando cartela cartela_29...
    Cadastrando cartela cartela_30...
    Cadastrando cartela cartela_31...
    Cadastrando cartela cartela_32...
    Cadastrando cartela cartela_33...
    Cadastrando cartela cartela_34...
    Cadastrando cartela cartela_35...
    Cadastrando cartela cartela_36...
    Cadastrando cartela cartela_37...
    Cadastrando cartela cartela_38...
    Cadastrando cartela cartela_39...
    Cadastrando cartela cartela_40...
    Cadastrando cartela cartela_41...
    Cadastrando cartela cartela_42...
    Cadastrando cartela cartela_43...
    Cadastrando cartela cartela_44...
    Cadastrando cartela cartela_45...
    Cadastrando cartela cartela_46...
    Cadastrando cartela cartela_47...
    Cadastrando cartela cartela_48...
    Cadastrando cartela cartela_49...
    Cadastrando cartela cartela_50...
    
    Iniciando o bingo...
    
    ################
    Pedra 1
    Numero sorteado = b'85'
    
    ################
    Pedra 2
    Numero sorteado = b'51'
    
    ################
    Pedra 3
    Numero sorteado = b'24'
    
    ################
    Pedra 4
    Numero sorteado = b'98'
    
    ################
    Pedra 5
    Numero sorteado = b'66'
    
    ################
    Pedra 6
    Numero sorteado = b'34'
    
    ################
    Pedra 7
    Numero sorteado = b'29'
    
    ################
    Pedra 8
    Numero sorteado = b'62'
    
    ################
    Pedra 9
    Numero sorteado = b'22'
    
    ################
    Pedra 10
    Numero sorteado = b'79'
    
    ################
    Pedra 11
    Numero sorteado = b'81'
    
    ################
    Pedra 12
    Numero sorteado = b'74'
    
    ################
    Pedra 13
    Numero sorteado = b'64'
    
    ################
    Pedra 14
    Numero sorteado = b'90'
    
    ################
    Pedra 15
    Numero sorteado = b'10'
    
    ################
    Pedra 16
    Numero sorteado = b'35'
    
    ################
    Pedra 17
    Numero sorteado = b'47'
    
    ################
    Pedra 18
    Numero sorteado = b'92'
    
    ################
    Pedra 19
    Numero sorteado = b'17'
    
    ################
    Pedra 20
    Numero sorteado = b'88'
    
    ################
    Pedra 21
    Numero sorteado = b'12'
    
    ################
    Pedra 22
    Numero sorteado = b'45'
    
    ################
    Pedra 23
    Numero sorteado = b'93'
    
    ################
    Pedra 24
    Numero sorteado = b'1'
    
    ################
    Pedra 25
    Numero sorteado = b'72'
    
    ################
    Pedra 26
    Numero sorteado = b'38'
    
    ################
    Pedra 27
    Numero sorteado = b'56'
    
    ################
    Pedra 28
    Numero sorteado = b'99'
    
    ################
    Pedra 29
    Numero sorteado = b'95'
    
    ################
    Pedra 30
    Numero sorteado = b'52'
    
    ################
    Pedra 31
    Numero sorteado = b'13'
    
    ################
    Pedra 32
    Numero sorteado = b'48'
    
    ################
    Pedra 33
    Numero sorteado = b'36'
    
    ################
    Pedra 34
    Numero sorteado = b'5'
    
    ################
    Pedra 35
    Numero sorteado = b'65'
    
    ################
    Pedra 36
    Numero sorteado = b'96'
    
    ################
    Pedra 37
    Numero sorteado = b'20'
    
    ################
    Pedra 38
    Numero sorteado = b'77'
    
    ################
    Pedra 39
    Numero sorteado = b'15'
    
    ################
    Pedra 40
    Numero sorteado = b'78'
    
    ################
    Pedra 41
    Numero sorteado = b'58'
    
    ################
    Pedra 42
    Numero sorteado = b'59'
    
    ################
    Pedra 43
    Numero sorteado = b'30'
    
    ################
    Pedra 44
    Numero sorteado = b'44'
    
    ################
    Pedra 45
    Numero sorteado = b'84'
    
    ################
    Pedra 46
    Numero sorteado = b'26'
    
    ################
    Pedra 47
    Numero sorteado = b'23'
    
    ################
    Pedra 48
    Numero sorteado = b'94'
    
    ################
    Pedra 49
    Numero sorteado = b'76'
    
    ################
    Pedra 50
    Numero sorteado = b'18'
    
    ################
    Pedra 51
    Numero sorteado = b'71'
    
    ################
    Pedra 52
    Numero sorteado = b'16'
    
    ################
    Pedra 53
    Numero sorteado = b'11'
    
    ################
    Pedra 54
    Numero sorteado = b'69'
    
    ################
    Pedra 55
    Numero sorteado = b'43'
    
    ################
    Pedra 56
    Numero sorteado = b'54'
    
    ################
    Pedra 57
    Numero sorteado = b'61'
    
    ################
    Pedra 58
    Numero sorteado = b'49'
    
    ################
    Pedra 59
    Numero sorteado = b'80'
    
    ################
    Pedra 60
    Numero sorteado = b'21'
    
    ################
    Pedra 61
    Numero sorteado = b'19'
    
    ################
    Pedra 62
    Numero sorteado = b'28'
    
    ################
    Pedra 63
    Numero sorteado = b'63'
    
    ################
    Pedra 64
    Numero sorteado = b'53'
    
    ################
    Pedra 65
    Numero sorteado = b'70'
    
    ################
    Pedra 66
    Numero sorteado = b'57'
    
    ################
    Pedra 67
    Numero sorteado = b'8'
    
    ################
    Pedra 68
    Numero sorteado = b'55'
    
    ################
    Pedra 69
    Numero sorteado = b'39'
    
    ################
    Pedra 70
    Numero sorteado = b'67'
    
    ################
    Pedra 71
    Numero sorteado = b'87'
    
    ################
    Pedra 72
    Numero sorteado = b'75'
    
    ################
    Pedra 73
    Numero sorteado = b'37'
    
    ################
    Pedra 74
    Numero sorteado = b'73'
    
    ################
    Pedra 75
    Numero sorteado = b'42'
    
    ################
    Pedra 76
    Numero sorteado = b'25'
    
    ################
    Pedra 77
    Numero sorteado = b'91'
    
    ################
    Pedra 78
    Numero sorteado = b'9'
    
    ################
    Pedra 79
    Numero sorteado = b'68'
    
    ################
    Pedra 80
    Numero sorteado = b'60'
    
    ################
    Pedra 81
    Numero sorteado = b'89'
    
    ################
    Pedra 82
    Numero sorteado = b'83'
    
    O bingo terminou.

#### Ganhador

    O vencedor foi o user_25.
    
#### Ranking

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Usuário</th>
      <th>Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>24</th>
      <td>user_25</td>
      <td>15</td>
    </tr>
    <tr>
      <th>10</th>
      <td>user_11</td>
      <td>14</td>
    </tr>
    <tr>
      <th>20</th>
      <td>user_21</td>
      <td>14</td>
    </tr>
    <tr>
      <th>39</th>
      <td>user_40</td>
      <td>14</td>
    </tr>
    <tr>
      <th>13</th>
      <td>user_14</td>
      <td>14</td>
    </tr>
    <tr>
      <th>23</th>
      <td>user_24</td>
      <td>14</td>
    </tr>
    <tr>
      <th>11</th>
      <td>user_12</td>
      <td>14</td>
    </tr>
    <tr>
      <th>25</th>
      <td>user_26</td>
      <td>14</td>
    </tr>
    <tr>
      <th>7</th>
      <td>user_8</td>
      <td>14</td>
    </tr>
    <tr>
      <th>47</th>
      <td>user_48</td>
      <td>14</td>
    </tr>
    <tr>
      <th>2</th>
      <td>user_3</td>
      <td>14</td>
    </tr>
    <tr>
      <th>37</th>
      <td>user_38</td>
      <td>13</td>
    </tr>
    <tr>
      <th>18</th>
      <td>user_19</td>
      <td>13</td>
    </tr>
    <tr>
      <th>26</th>
      <td>user_27</td>
      <td>13</td>
    </tr>
    <tr>
      <th>27</th>
      <td>user_28</td>
      <td>13</td>
    </tr>
    <tr>
      <th>22</th>
      <td>user_23</td>
      <td>13</td>
    </tr>
    <tr>
      <th>36</th>
      <td>user_37</td>
      <td>13</td>
    </tr>
    <tr>
      <th>19</th>
      <td>user_20</td>
      <td>13</td>
    </tr>
    <tr>
      <th>16</th>
      <td>user_17</td>
      <td>13</td>
    </tr>
    <tr>
      <th>41</th>
      <td>user_42</td>
      <td>13</td>
    </tr>
    <tr>
      <th>44</th>
      <td>user_45</td>
      <td>13</td>
    </tr>
    <tr>
      <th>45</th>
      <td>user_46</td>
      <td>13</td>
    </tr>
    <tr>
      <th>12</th>
      <td>user_13</td>
      <td>13</td>
    </tr>
    <tr>
      <th>8</th>
      <td>user_9</td>
      <td>13</td>
    </tr>
    <tr>
      <th>5</th>
      <td>user_6</td>
      <td>13</td>
    </tr>
    <tr>
      <th>3</th>
      <td>user_4</td>
      <td>13</td>
    </tr>
    <tr>
      <th>31</th>
      <td>user_32</td>
      <td>13</td>
    </tr>
    <tr>
      <th>32</th>
      <td>user_33</td>
      <td>12</td>
    </tr>
    <tr>
      <th>46</th>
      <td>user_47</td>
      <td>12</td>
    </tr>
    <tr>
      <th>48</th>
      <td>user_49</td>
      <td>12</td>
    </tr>
    <tr>
      <th>35</th>
      <td>user_36</td>
      <td>12</td>
    </tr>
    <tr>
      <th>34</th>
      <td>user_35</td>
      <td>12</td>
    </tr>
    <tr>
      <th>0</th>
      <td>user_1</td>
      <td>12</td>
    </tr>
    <tr>
      <th>4</th>
      <td>user_5</td>
      <td>12</td>
    </tr>
    <tr>
      <th>6</th>
      <td>user_7</td>
      <td>12</td>
    </tr>
    <tr>
      <th>9</th>
      <td>user_10</td>
      <td>12</td>
    </tr>
    <tr>
      <th>17</th>
      <td>user_18</td>
      <td>11</td>
    </tr>
    <tr>
      <th>42</th>
      <td>user_43</td>
      <td>11</td>
    </tr>
    <tr>
      <th>14</th>
      <td>user_15</td>
      <td>11</td>
    </tr>
    <tr>
      <th>15</th>
      <td>user_16</td>
      <td>11</td>
    </tr>
    <tr>
      <th>43</th>
      <td>user_44</td>
      <td>11</td>
    </tr>
    <tr>
      <th>49</th>
      <td>user_50</td>
      <td>11</td>
    </tr>
    <tr>
      <th>40</th>
      <td>user_41</td>
      <td>11</td>
    </tr>
    <tr>
      <th>38</th>
      <td>user_39</td>
      <td>11</td>
    </tr>
    <tr>
      <th>1</th>
      <td>user_2</td>
      <td>11</td>
    </tr>
    <tr>
      <th>29</th>
      <td>user_30</td>
      <td>11</td>
    </tr>
    <tr>
      <th>28</th>
      <td>user_29</td>
      <td>10</td>
    </tr>
    <tr>
      <th>33</th>
      <td>user_34</td>
      <td>10</td>
    </tr>
    <tr>
      <th>21</th>
      <td>user_22</td>
      <td>9</td>
    </tr>
    <tr>
      <th>30</th>
      <td>user_31</td>
      <td>8</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
