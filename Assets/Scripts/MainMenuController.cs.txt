using UnityEngine;
using UnityEngine.SceneManagement;

public class MainMenuController : MonoBehaviour
{
    public void PlayGame()
    {
        SceneManager.LoadScene("SampleScene"); // Change to your game scene's name
    }

    public void QuitGame()
    {
        Application.Quit();
    }
}
