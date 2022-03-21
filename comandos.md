git checkout -b <<nome da branc>>
-- Cria uma branch nova a partir da branch em que o usuario está

-- Cria uma branch nova a partir da branch em que o usuario está.
git pull origin <<nome da branch>>

-- Faz a mesclagem das branchs, sem necessidade de commit apenas atualiza o que está na branch <<>> e joga na branch atual.

git merge --no-ff <<nome da branch>>
-- Faz a mesclagem das branchs, mas informa que hou uma mesclagem ataraves de um commit de merge.
