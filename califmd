<body>
            <declare name="ContAprob" type="Integer" array="False" size=""/>
            <assign variable="ContAprob" expression="0"/>
            <declare name="ContNA" type="Integer" array="False" size=""/>
            <assign variable="ContNA" expression="0"/>
            <declare name="Promedio" type="Real" array="False" size=""/>
            <declare name="Calif" type="Real" array="False" size=""/>
            <assign variable="Calif" expression="0"/>
            <declare name="suma" type="Real" array="False" size=""/>
            <assign variable="suma" expression="0"/>
            <declare name="i" type="Integer" array="False" size=""/>
            <for variable="i" start="1" end="5" direction="inc" step="1">
                <output expression="&quot;Escribe la calificacion&quot;" newline="True"/>
                <input variable="Calif"/>
                <if expression="Calif&gt;=1 AND Calif&lt;=10">
                    <then>
                        <if expression="Calif &gt;= 7">
                            <then>
                                <assign variable="ContAprob" expression="ContAprob+1"/>
                            </then>
                            <else>
                                <assign variable="ContNA" expression="ContNA + 1"/>
                            </else>
                        </if>
                        <assign variable="suma" expression="suma + Calif"/>
                    </then>
                    <else>
                        <do expression="Calif&gt;10">
                            <do expression="Calif&lt;1">
                                <output expression="&quot;Calificacion erronea&quot;" newline="True"/>
                                <output expression="&quot;Escriba una calificacion valida&quot;" newline="True"/>
                                <input variable="Calif"/>
                            </do>
                        </do>
                        <if expression="Calif &gt;= 7">
                            <then>
                                <assign variable="ContAprob" expression="ContAprob+1"/>
                            </then>
                            <else>
                                <assign variable="ContNA" expression="ContNA + 1"/>
                            </else>
                        </if>
                        <assign variable="suma" expression="suma + Calif"/>
                    </else>
                </if>
            </for>
            <assign variable="Promedio" expression="suma / 5"/>
            <output expression="&quot;Promedio es&quot;" newline="True"/>
            <output expression="Promedio" newline="True"/>
            <output expression="&quot;Aprobadas son&quot;" newline="True"/>
            <output expression="ContAprob" newline="True"/>
            <output expression="&quot;Reprobadas son&quot;" newline="True"/>
            <output expression="ContNA" newline="True"/>
        </body>
