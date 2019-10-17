# Vaja3-ADC-trigger-timer-conversion-STM32F0

# Odgovori na vprašanja

b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PC0.

e) Kaj se izpiše poleg pina? ADC_IN10

h) Aktiviramo samo zeleno LED diodo na ustreznem izhodu - PC9 

i) Kaj opazite? Spremenijo se izhodne frekvence 

l) V configuration kliknemo gumb za TIM1, ki je v polju Control. Časovniku bi radi spremenili frekvenco na 1kHz, zato moramo frekvenca ABP1 Timer Clock preskalirati v polju
   Prescaler (PSC - 16 bit value). Koliko znaša ta vrednost? 16.000 

f) Uporabite metodo TogglePin iz HAL knjižnice in zapišite ukaz: HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9)

# Komentar

S potenciometrom spreminjamo vrednost ADC pretvorb sproženih s časovnimi prekinitvami.
