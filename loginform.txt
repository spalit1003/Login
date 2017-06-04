/**
 * Sample React Native App
 * https://github.com/facebook/react-native
 * @flow
 */

import React, { Component } from 'react';
import
{
    AppRegistry,
    StyleSheet,
    Text,
    TextInput,  View, TouchableOpacity
} from 'react-native';


export default class AwesomeProject extends Component

    {
        render()
        {

            return (

                       <View style= {styles.container}>


                                    <TextInput style= {styles.input}
                                            placeholder="Email"
                                                    placeholderTextColor='grey'
                                                            />

                                                            <TextInput style = {styles.input}
                                                                    placeholder="Password"
                                                                            placeholderTextColor='grey'
                                                                                    secureTextEntry
                                                                                    />
                                                                                    <TouchableOpacity style= {styles.logContainer}>
                                                                                            <Text style= {styles.logText}>LOGIN</Text>
                                                                                                    </TouchableOpacity>

                                                                                                    <TouchableOpacity>
                                                                                                    <Text style= {styles.checkText}>Don't have an account?</Text>
                                                                                                            </TouchableOpacity>

                                                                                                            <TouchableOpacity style={styles.signContainer}>
                                                                                                            <Text style={styles.signText}>SIGN UP</Text>
                                                                                                            </TouchableOpacity>

                                                                                                            <TouchableOpacity>
                                                                                                            <Text style={styles.checkText}>Forgot Password</Text>
                                                                                                            </TouchableOpacity>



                                                                                                            </View>

                                                                                                            );

                                                                                                        }
                                                                                                        }


                                                                                                            const styles = StyleSheet.create({

                                                                                                            container: {

                                                                                                            paddingVertical:'18%',
                                                                                                            flex: 1,

                                                                                                            justifyContent: 'flex-start',

                                                                                                            alignItems: 'center',

                                                                                                            backgroundColor: 'white',

                                                                                                        },



                                                                                                            input:{
                                                                                                            height:70,
                                                                                                            marginBottom:25,
                                                                                                            backgroundColor:'white',
                                                                                                            color: '#00ced1',
                                                                                                            width:'80%',
                                                                                                            fontSize:17,
                                                                                                        },

                                                                                                            logContainer:{
                                                                                                            position: 'relative',
                                                                                                            backgroundColor: '#00ced1',
                                                                                                            paddingVertical: 14,
                                                                                                            width:'80%',
                                                                                                            borderRadius:4,
                                                                                                            borderWidth:2,
                                                                                                            borderColor:'#00ced1',
                                                                                                            margin:40,
                                                                                                        },

                                                                                                            logText:{
                                                                                                            textAlign: 'center',
                                                                                                            color: 'white',
                                                                                                            fontWeight: "700",
                                                                                                            fontSize:20,
                                                                                                        },

                                                                                                            checkText:{
                                                                                                            textAlign: 'center',
                                                                                                            color: '#00ced1',
                                                                                                            fontWeight: "700",
                                                                                                            fontSize:20,
                                                                                                        },

                                                                                                            signContainer:{
                                                                                                            backgroundColor: 'white',
                                                                                                            paddingVertical: 14,
                                                                                                            width:'80%',
                                                                                                            borderColor:'#00ced1',
                                                                                                            borderWidth:2,
                                                                                                            borderRadius:4,
                                                                                                            margin:10,
                                                                                                        },

                                                                                                            signText:{
                                                                                                            textAlign: 'center',
                                                                                                            color: '#00ced1',
                                                                                                            fontWeight: "700",
                                                                                                            fontSize:20,

                                                                                                        },
                                                                                                        }); AppRegistry.registerComponent('AwesomeProject', () => AwesomeProject);

