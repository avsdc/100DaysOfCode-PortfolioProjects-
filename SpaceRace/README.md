**Highlights Of The Space Race**

With the end of World War II, a new conflict started between the two superpowers, the US and Soviet Union. This war known as the Cold War, effected all aspects of life in both countries, and shaped the politics of the two nations until the breakup of the Soviet Union in 1991.

The highlights of the Cold War era were the arms race, nuclear weapons development by both nations, espionage, counter-espionage etc. Events such as the building of the Berlin War in 1961, the Cuban Missile crisis of 1962, and outbreak of war in southeast Asia, only added more fuel to the Cold War.  The competition between the two, and the tensions therefore, extended to the Space Race too.

The Soviets were ahead to begin with. In 1957, their R-7 ICBM launched the Sputnik. It was the world's first satellite, and man-made object to be put into the earth's orbit. This was a challenge for the US. As a response, in 1958, the US President, Dwight D.Eisenhower, created the NASA, a federal agency for the purpose of space exploration.

In 1959, the Soviets launched the Luna2, the first space probe to the moon. In 1961, Yuri Gagarin, became the first human being to travel in capsule-like spacecraft, Vostok 1, orbiting the earth. The Americans were not to be left behind in this race. They created a lighter spacecraft than the Vostok, and tested the spacecraft with chimpanzees. On May 5, that year, Alan Shepherd became the first American in space.

Later in May 1961, the then US President claimed that the Americans would put the first humans on the moon, before the end of the decade. By the following year, NASA's lunar landing program, Project Apollo was started. On July 16, 1969, the US launched Apollo 11 with three American astronauts, Neil Armstrong, Aldrin onboard, and Armstrong became the first man to walk on the moon's surface.

Once the goal of landing American astronauts on the moon was achieved, the US government's interest in missions to the moon waned.

The 1970s also marked the entry of other players into the Space Race.
1970 saw Japan's Lambda 4 rocket launch its test satellite, Ohsumi. The same year, China, launched its first satellite, Dong Fang Hong-1, on its Lunar March 1 rocket.

In 1975, the European Space Agency was formed, and launched its first satellite Cos-B on its Thor-Delta rocket After 1975, European countries both individually and cooperatively through the European Space Agency, worked together on space missions.


The 1970s saw the beginnings of space missions to other planets. In 1971, the Mariner 9, orbited Mars.
In 1976,  the American probe,Viking 2, discovered water-frost on the Martian surface. Voyager 1 and Voyager 2 started transmitting images of Jupiter and its moons, in 1979. The same year, American probe Pioneer 11, reached Saturn, and also started transmitting images. 


American space missions continued into the 1980s. In 1980, Voyager 1, reached Saturn and started transmitting images. In 1981, Columbia became the first space shuttle to be launched, and in the same year, Voyager 2, also reached Saturn, and started transmitting images. Other space shuttles launched in this decade were Challenger, Discovery, and Atlantis. There were some successes, and there were some failures. 

The mid-1980s, Japan with its Sakigake, did a Halley's comet flyby. The European Space Agency's Giotto also flew by Halley comet.

In 1984, President Reagan  gave approval to the ISS (International Space Station). Apart from the US, Canada, Japan and member countries of the ESA  participated in the program. During the redesign of the program, in 1993, Russia was also invited to participate. The program was to be carried out in two phases. In Phase 1, NASA space shuttles would transport cosmonauts and astronauts to the Mir Orbital Space Station. The US would help to modify two Russian modules so as to work on US and international experiments, and to establish working connections between the participating countries. I
During Phase 2, headed by US and Russia, elements and crewmembers would be contributed by other participating countries. 

The goal of the ISS was to provide an education platform for youngsters to motivate them to pursue careers in STEM. All the participating agencies are united in their goal of applying knowledge gained through the ISS program to various fields of science, engineering and technology.

The program's greatest challenges and achievements are in unifying global agencies with varying cultural differences, that face restrictions due to politics, in order to operate the ISS. The program brought together international crew and globally distributed launch, operations, training, scientific, engineering, communications network communities. The ISS is to operate until at least 2030.

In 1986, space shuttle Challenger, exploded seconds after liftoff. In 1989, Voyager 2, started 
transmitting images from Neptune. The highlights of 1990, was the Magellan spacecraft's mapping of the Venus surface, and deployment of the Hubble Telescope by Discovery. In 1992, space shuttle Endeavor was launched, and in the following year, Endeavor began its servicing mission of the Hubble Telescope.

In 1997, the Mars Pathfinder arrived on Mars, and started transmitting messages. The year 2008, saw the NASA probe, Messenger, orbit the planet Mercury, 124 miles above its' surface. Chandrayaan 1, the Lunar Orbiter, marked the entry of another Asian nation, India's ISRO, to the space race. In 2010, China's Lunar Orbiter, Chang'e 2 orbited the moon. In 2009, NASA's Kepler spacecraft was launched to study planets outside of the Earth's solar system, in a distant area of the Milky Way. 

The year 2010, saw the entry of private organisations into the Space Race. Virgin Galactic announced a successful manned glide flight of VSS Enterprise. It was a suborbital plane, which was for the purpose of taking private citizens on sub-orbital flights. This was also the year which marked the entry of Space-X, a non-governmental organization. It successfully launched a spacecraft into orbit, and returned it to earth.

Into the 21st century, more than 50 countries have space agencies or other government bodies, that are working on space missions.






**Correlation Of Plots And Charts With Space Missions**

The dataset SpaceCorrected.csv was used for this project. It had 4324 rows, and 7 columns. 

There was 1 duplicate, and the Rocket column had some NaN values. These NaN values were replaced with 0.0, since the values in this column are floats, and maybe needed for calculation.

The Location column was converted to string and then used apply and lambda to obtain the Country column. Similarly, used apply and lambda to obtain the Year, Month and Date from the Datum column.

For the Plotly Donut chart, the column 'Status Rocket' of the df_data dataframe with value_counts(), was used to plot the pie chart for active and inactive missions.
The plot indicates that there are 81.7% retired rockets, and 18.3% active ones.

A Bar chart was plotted for the number of launches per organization for the df_data dataframe with 'Company Name' column and value_counts(). The top 6 companies are the RVSN of the USSR, Arianespace, CASC, General Dynamics, NASA and VKS RF.
RVSN had the maximum launches, and was way ahead of all the others.


The Pie chart for the percentage per country and year was created using country_yearly_launches, that was in turn obtained by grouping df_data dataframe by 'Country' and 'Year', using value_counts(), and creating a new column 'counts'.
Russia had the highest 32.3%, USA had 31.1%, and Kazhakstan had 16.2%.
A Bar chart for the number of launches per country also shows the highest number of launches were carried out by Russia, USA, and Kazhakstan.
The seaborn countplot also shows the same three countries with the highest number of launches.

A Bar chart for the total expenditure on space launches by organizations, shows NASA in the lead. It is way above all the rest. NASA is followed by Arianespace, and ULA.
As far as the expenditure on space missions by various countries is concerned, the Bar chart shows USA way above the rest. USA is followed by France, and Kazhakstan.

The Bar Chart for the Total Price Per Year For All Participating Countries shows that between 1967 and 1973, there was a spurt in the expenditure on space missions. This ties in with the Apollo missions to the moon of the late 1960's and early 1970's funded by the government. After that, until the 1980's the chart shows minimal expenditure, just as mentioned in the report above. This was due to loss of government interest in missions to the moon, as well as public opinion The chart continues to show expenditure throughtout the 1980s. There were a lot of American space missions, but to other planets.

The late 1980s show a rise in expenditure. In fact, the maximum expenditure since the space race began, is seen in 1987, and 1988. During these years, USA launched space shuttles, Challenger, Discovery, and Endeavor. Endeavor also deployed the Hubble Space Telescope, and started servicing the telescope. 
The ISS program was also created in 1984, and US worked with Canada, Japan and ESA on this program. The program was further extended after Russia joined  in 1993.


There is again increased expenditure on space missions into the 21st century, especially after 2006, as the chart indicates. This is due to entry into the space race by private organisations such as Space X, and other nations also carrying out their own space missions, such as China, Japan and India.

The Bar chart for price per organization split by Active and Inactive Rockets, shows maximum expenditure by RVSN USSR, which are inactive now, followed by General Dynamics and NASA that are also inactive. This is followed by CASC(China) that has active rockets. Arianespace ties with CASC as far as expenditure is concerned, but many of its rockets are now inactive. These two are followed by ULA, that has some active rockets.

The sns countplot also shows that many rockets of various nations are now retired or inactive.

The Bar chart for mission status per organization shows RVSN USSR, with the the maximum launches. About half of these appear to be successes, and rest failures. General Dynamics follows with the same proportion of successes and failures.  This is followed by US AirForce, which seems to have more failures. Next is NASA, with more successes than failures.

The histogram for organizations and their success, failure, pre-launch failure, and partial failure shows RVSN USSR has the maximum number of launches with several successes, and some failures. This is followed by Arianespace with many successes and fewer failures. Third is General Dynamics with many successes, and few failures.

The histogram plot shows the 4 different types of outcomes of the missions. These are Success, Failure, Pre-Launch Failure, and Partial failure.
To plot the chlopleth map a new 'ISO' column was created in the df_data dataframe, to provide codes for countries. The apply and lambda function are applied to df_data['Country'] column, and a parameter country is passed to the iso function. Inside the iso function, pycountry is used to retrieve the ISO codes for countries, and the 'ISO' column is created. The df_iso is the df_data['ISO'] column with value_counts().
In the chloropleth map, the darker colors from the color bar to the right of the map, are applied to Russia, followed by USA, and Kazhakstan. This indicates that these three nations have the maximum number of launches in that order. France and China are colored pale orange, indicating that they are next after Russia, USA and Kazhakstan in terms of number of launches. India follows next as far as the number of launches is concerned, and it is colored a slightly darker yellow than New Zealand, Australia, Kenya, Brazil, and Iran which follow in the number of launches.

Bar chart for number of launches per year show that there were many launches from  1965 to 1978.  There also seem to be more launches between 2016 until 2020.
As far as the months are concerned, December has the maximum number of launches followed by June. April and October tie for the third place. January is the least favorable month for launches. 
Wednesday, Thursday, Friday in that order have the maximum number of launches. Sunday has the least number of launches.

The bar chart for top 10 organisations in terms of price of their space missions is concerned show the following organisations in the order of  RVSN USSR, Arianespace, General Dynamics, CASC, NASA, VKS RF, US Air Force, ULA, Boeing, and Martin Marietta.

The Sunburst chart show USSR, USA, Kazhakstan, China, India in the space race. The US companies include NASA, General Dynamics, US Air Force, ULA, Boeing, Space X, Lockheed, Northrop, US Navy and ILS. The Russian companies include RVSN USSR and VKS RF. RVSN USSR was also responsible for launches from Kazhakstan.
Arianespace carried out launches for France.
The Chinese company carrying out launches is the CASC. MHI is the Japanese company involved in space missions, and for India it is the ISRO. While all these companies have some failures, most of them are successes.

The dataframe superpower_launches is created by concatenating usa_launches and russia_launches.  A pie chart is then created using superpower_launches dataframe. This chart shows that of the total expenditure of both usa and russia put together, usa contributed 98% and rest russia.

The next plot which is a donut pie chart, indicates that of the total launches by superpowers, 90.9% were successes, 6.9% were failures, 2.19% were partial failures.
The next plot which is also a donut pie chart, shows yearly launches of the superpowers, and uses the superpower_launches dataframe.

The last chart also uses superpower_launches, and displays the year on the X-axis, and expenditure for launches on the Y-axis by the superpowers. Maximum expenditure is seen in 1969. This is when US launched Apollo 11, and Neil Armstrong became the first astronaut to land on the moon.
