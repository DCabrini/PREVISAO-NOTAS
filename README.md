Os dados consistem em características de escolas e alunos, sendo que o objetivo da modelagem é prever o resultado no exame normalizado (normexam) de acordo com as características dos alunos e das escolas.
O modelo deve ser capaz de responder quais do tipo de escola (gênero misto, só de homens ou só de mulheres) é mais eficiente na formação de seus alunos de acordo com o resultado do exame normalizado.

# Legenda

#' | variável | Descrição                                                                                                         |

#' |----------|------------------------------------------------------------------------------------------------------------------ |

#' | school   | ID escolar.                                                                                                       |

#' | normexam | Pontuação do exame normalizada.                                                                                   |

#' | schgend  | gênero escolar - são 'mixed', 'boys', e 'girls'.                                                                  |

#' | schavg   | média escolar de pontuação de admissão.                                                                           |

#' | vr       | faixa de pontuação de raciocínio verbal (VR) no nível do aluno na admissão - 'bottom 25%', 'mid 50%', e 'top 25%'.|

#' | intake   | faixa de pontuação de admissão do aluno - são 'bottom 25%', 'mid 50%' e 'top 25%'./                               |

#' | standLRT | Pontuação padronizada do teste LR.                                                                                |

#' | sex      | Sexo do aluno - são 'F' and 'M'.                                                                                  |

#' | type     | Tipo de escola - são 'Mxd' and 'Sngl'.                                                                            |

#' | student  | ID do aluno (dentro da escola)                                                                                    |

# Arquivos:
 cat_school_data.csv Variáveis categóricas que são aplicadas às escolas.
 num_school data.csv Variáveis numéricas que são aplicadas às escolas.
 cat_student data.csv Variáveis categóricas que são aplicadas aos estudantes.
 num_student_data.csv Variáveis numéricas que são aplicadas aos estudantes.
