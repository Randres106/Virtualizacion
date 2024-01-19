# Virtualizacion
Rafael Alvarez 1018419 __
Carlos Vargas  1125417 __
María Caneses  1187820 __
<br> 
const fetchData = async (endpoint) => {
    try {
      const response = await axios.get(${REACT_APP_API_ENDPOINT}/${endpoint});
      return response.data.value;
    } catch (error) {
      console.error(error);
      throw error;
    }
  };
